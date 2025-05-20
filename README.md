
VR Concert & Cultural Event Experience Website

An immersive browser-based VR platform that simulates real-life concerts and cultural events. Built using HTML, CSS, and JavaScript with support for 3D models, videos, and avatar personalization, the website provides an engaging 360° experience using `.glb` assets and spatial elements.

for all the concert videos,the website demo video,the glb charactes and the presentation : 
https://drive.google.com/drive/folders/1GtwG8Ya0Gbbf7uOWpg8WbCg7ULnlDdwj?usp=drive_link

Key Features

Multi-Genre Virtual Concerts
  Individual HTML pages for Pop, Rock, EDM, Rap, Russian, and more — each simulating a unique concert experience.

3D Artists and Crowds
  `.glb` models like `travis_scott.glb`, `crowd.glb`, `black_bikini.glb`, etc., used to represent performers and audiences.

Custom Avatar Integration
  Avatar creation and scanning enabled through `avatar-scan.html`, integrating with external APIs for user personalization.

Immersive Video + Audio Playback
  Videos (`alanwalker.mp4`, `travis.mp4`, etc.) embedded across concert pages for realistic playback.

Genre-Specific Events
  Dedicated HTML files like `pop.html`, `rock.html`, `rap.html`, and `edm.html` deliver genre-tailored environments.

Folder Structure
├── .vscode/ 
├── node_modules/ 
├── public/ 
├── .gitattributes
├── .nojekyll 
├── .Rhistory 
├── .html 
├── .js 
├── .css 
├── .mp4 
├── .glb 
├── package.json 
├── README.md 
└── Presentation.pdf 

Tech Stack

 Purpose     -  Tools Used                       
Web Framework - HTML5, CSS3, JavaScript          
3D Rendering  - Three.js (assumed for .glb usage)
3D Assets    - `.glb` models for scenes & avatars
Video         - HTML5 `<video>` elements          
API           -Avatar creation & customization   
Hosting       - Glitch / GitHub Pages compatible  


Usage Guide
Navigate to index.html for the homepage.
Select from genres: pop.html, rock.html, rap.html, edm.html, russian.html, etc.
Avatar creation and scanning: Open avatar-scan.html.
3D scenes and video playback are embedded within each genre page.

Assets Used
3D Models (.glb)
character.glb – Base avatar model
crowd.glb – Audience animation
travis_scott.glb – Artist representations
Videos (.mp4)
alanwalker.mp4, travis.mp4, xxxtenc.mp4 – Concert footage
compressed.mp4 – Optimized for faster loading

Demo & Presentation
Demo Videos:
demo_video (2).mp4 – Main demo
Presentation:
Presentation (2).pdf – Slides explaining features and design


License
MIT License. Free to use and modify with credit.

Acknowledgements
.glb models from Sketchfab and Free3D
Music videos from artist-owned sources for demo purposes only
Inspired by real-world concerts and cultural diversity


