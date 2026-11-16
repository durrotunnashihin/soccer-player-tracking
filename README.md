# Soccer Player Tracking and Team Classification from Broadcast Highlights: a Lightweight Analytical Pipeline

<img width="1842" height="1034" alt="Player Tracking-Page-2 (5)" src="https://github.com/user-attachments/assets/8f8b0952-4aca-48a0-8c0c-ac9ba0199624" />


# 📝 Overview
This project provides a lightweight, low-cost pipeline for soccer player tracking and team classification using only broadcast highlight videos. The system uses YOLOv8 for player detection, ByteTrack for multi-object tracking, and KMeans clustering on HSV jersey colors with a majority-based correction for team classification. Simple preprocessing steps (i.e., frame skipping, field masking, and session segmentation) enable robust performance even under challenging broadcast conditions.

The entire workflow is designed to be run inside Google Colab, and each notebook already includes an Install Libraries section (**no manual setup or pip install -r requirements.txt is required**).

# 🎥 Demo Video (YouTube Output)
Full demo video on YouTube: https://www.youtube.com/watch?v=5i48wgPQ_34

# 🔍 Key Features
1. 🎥 Input: Broadcast highlight video (source: https://www.youtube.com/watch?v=ffAYByv2pLc)
2. 🧩 Player Detection: YOLOv8
3. 🔗 Player Tracking: ByteTrack
4. 🎨 Team Classification: KMeans clustering on HSV jersey colors + temporal majority correction
5. ⚽ Analytics Output: Movement patterns, team visibility, coarse movement pattern, average on-screen position

# 🚀 How to Run (Google Collab)
1. Clone this repository (https://github.com/durrotun04/soccer-player-tracking.git)
2. Upload the project folder (soccer-player-tracking) into: My Drive/Colab Notebooks/
3. Make sure your structure looks like this:
  
   <img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/b6273f8e-a45b-4205-b262-56c8ecee5b87" />

4. Run all cells

Everything is preconfigured, **so no path editing is required.**

# 📜 Citation
If you use this repository, please cite:

**IEEE Style**
Nashihin, D., Panduman, Y. Y. F., Al Ardha, M. A., Noordia, A., and Yahya, S., “Soccer Player Tracking and Team Classification from Broadcast Highlights: A Lightweight Analytical Pipeline,” _Passer Journal of Basic and Applied Sciences_, vol. 8, no. 2, pp. 1167–1174, 2026, doi: 10.24271/PSR.2026.579319.2720.

**APA 7th Edition**
Nashihin, D., Panduman, Y. Y. F., Al Ardha, M. A., Noordia, A., & Yahya, S. (2026). Soccer player tracking and team classification from broadcast highlights: A lightweight analytical pipeline. _Passer Journal of Basic and Applied Sciences_, 8(2), 1167–1174. https://doi.org/10.24271/PSR.2026.579319.2720

# 🤝 Contributions
Contributions, pull requests, and discussions are welcome!
Feel free to open issues for bugs, suggestions, or improvements.


