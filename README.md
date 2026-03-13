# Construction-Progress-Recognition
## Project Background
Covers construction phases: foundation, main structure, exterior/enclosure (walls, doors & windows, roof), and interior finishing & MEP installation.
Many construction steps look visually similar in images but correspond to different progress stages.
## Project Goals
Traditional construction progress tracking relies on manual inspection and record-keeping, which has several limitations:
Delayed updates: Hard to detect construction delays in real time.
Low efficiency: Manual inspections are time-consuming for high-rise or large-scale projects.
Subjective records: Human error and inconsistent standards.
Poor traceability: Paper or Excel records are difficult to analyze historically or visualize.
## Solution – Multi-Stage Progress Recognition
Stage 1 – Coarse-grained recognition
High-frequency, distinctive construction steps are identified via high-accuracy image matching to provide a rough progress estimate.
Stage 2 – Fine-grained recognition
vLLM fine-tunes the progress estimation for precise output, which is automatically uploaded to the project management platform.
## Tech Stack
Image & annotation storage → MinIO
Vector storage & retrieval → Milvus + ResNet
Progress optimization → vLLM
