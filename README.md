# CVInternship_HighlightSegmentsFromVideo
Match Highlights Extractor
This project automatically extracts highlight-worthy segments from full-length match clips by identifying high-action frames using computer vision techniques. It's designed to assist sports analysts, content creators, and fans by reducing long videos into dynamic highlight reels.

🎯 Objective
The goal is to detect and extract exciting moments (goals, fouls, celebrations, fast gameplay) from a football match clip by analyzing frame-level activity and motion, using a combination of OpenCV and frame scoring logic.

🛠️ Features
⚡ Frame Sampling – Extracts 1 frame per second from the match video.

📊 Motion Intensity Analysis – Detects high-action frames using optical flow and frame difference techniques.

🧠 Highlight Detection – Segments with high cumulative activity are marked as potential highlights.

✂️ Automatic Clipping – Extracts the corresponding video segments and saves them as highlight clips.

📁 Output Organized – Highlights are saved with timestamps and relevant metadata.

