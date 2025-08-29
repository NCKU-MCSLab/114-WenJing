# 114-WenJing
Dataset for Identify Conversation Partner in Egocentric Perspective using Head Pose, Audio Data and Dialogue Content,Master thesis ,2025
## MCSConverse dataset Dialogue script naming rule
0210_3P1.docx
- 0210 → Session recorded on February 10.
- 3P → Three participants took part in the conversation.
- 1 → This is experiment 1 carried out on February 10.

0619_[topic].docx
- 0619 → Session recorded on June 19.
- [topic]:3 different topics, restaurant ordering, travel planning, business meeting.
- Every experiment conducted on June 19 is design for 4 participants.

## MCSConverse dataset download
Our labeling rule is: person 1 is fixed as the conversation partner, person 2 is the non-conversation partner, and person 0 is the camera wearer.
For time synchronization between the data, we asked each participant to press the audio and video record buttons simultaneously during recording; therefore, there may still be time offsets between the videos.

raw video:

20 second clips:


## Synthetic dataset
You can download the original data from the official project pages:
- Candor corpus:   
  website:https://www.science.org/doi/10.1126/sciadv.adf3197   
  download url:https://betterup-data-requests.herokuapp.com/ (Registration required)
- Voxceleb2:  
  website:https://mm.kaist.ac.kr/datasets/voxceleb/#downloads (Registration required)
  Huggingface:https://huggingface.co/datasets/ProgramComputer/voxceleb

## Data Preparing tools
- Light-ASD  
Official implementation:[Junhua-Liao/Light-ASD]([https://github.com/shamangary/FSA-Net](https://github.com/Junhua-Liao/Light-ASD))

- FSA-Net  
Official implementation:[shamangary/FSA-Net](https://github.com/shamangary/FSA-Net)  
Pytorch implementation:[omasaht/headpose-fsanet-pytorch](https://github.com/omasaht/headpose-fsanet-pytorch)  


