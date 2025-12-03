# ICT-Practising-Games-For-Children

Incorporating the "Typing Trek" game as the primary example and detailing the project's structure and goals.

🎮 ICT Educational Games HubEngaging, Open-Source Games for Student Practice (HTML, CSS, & JavaScript)

This repository contains a dynamic and growing collection of interactive, browser-based educational games designed to provide school students (targeting Grade 6 and above) with a fun and practical way to practice key Information and Communications Technology (ICT) and foundational academic skills.

✨ Why This Project?Traditional learning often lacks engaging, hands-on practice, especially for skills like touch typing. This project aims to bridge that gap by offering:Active Learning: Students learn by doing, receiving instant feedback on accuracy and speed.

Accessibility: Games are built entirely using HTML, CSS, and vanilla JavaScript, requiring no specialized software—just a modern web browser.Open Source: The code is transparent, allowing educators, parents, and students to understand the mechanics, customize the content, and even contribute new games.🕹️ Featured Game: Typing TrekTyping Trek is a multi-level typing practice game focused on building muscle memory, accuracy, and rhythm, essential skills for any modern ICT curriculum.Game MechanicsFocus: Accuracy over speed, especially in early levels.Visual Feedback:Current Letter: Highlighted in Yellow ($\text{.current-letter}$).Correct Letter: Turns Green ($\text{.typed-correct}$).Error: Turns Red and requires correction before proceeding ($\text{.typed-incorrect}$).Progress Tracking: Real-time metrics for Accuracy and Time.Level Structure (Example)Level NameFocusGoalPractice Content1. Home Row CavesASDF JKL;Master Home Row positioning.Simple combinations: asdf jkl; a lad asks2. E/I/R/T ForestTop Row KeysIntroduce common high-use keys.Common 4-5 letter words: tear trail tile fast3. Punctuation PeakShift Key & PunctuationCapitalization and basic marks.Simple sentences: The fact is true. Did it fall?🛠️ Technology StackThis project prioritizes simplicity and accessibility using standard web technologies.HTML5: Provides the structure and content for the games.CSS3: Handles the game's visual presentation, layout, and styling.JavaScript (Vanilla ES6+): Implements the core game logic, including:Keyboard event listening ($\text{document.addEventListener('keydown', ...)}$).Game state management (tracking position, errors, and time).DOM manipulation for updating visual feedback and statistics.🚀 Getting StartedFollow these simple steps to get the games running locally on your computer.PrerequisitesYou only need a modern web browser (Chrome, Firefox, Edge, Safari, etc.).Installation and SetupClone the Repository:Bashgit clone https://github.com/YourUsername/ict-educational-games-hub.git
Navigate to the Project Directory:Bashcd ict-educational-games-hub

##How to run a game?
# method 1
  You can just copy a code of a single file and copy to your note pade and rename "gmaename.html" and run it, You can put any gmaename but ".html" is must
  Then you can open it with any browser

# method 2
  You can download the files and simply open it
  
Additional Support
==================
Run the Games:Locate the game file you wish to run (e.g., typing_trek.html inside the games/typing-trek folder).Double-click the HTML file. It will open directly in your default web browser and the game will be ready to play.💡 How to Customize ContentEducators can easily customize the learning material without touching the core game logic.Open the specific game's HTML file (e.g., typing_trek.html).Locate the JavaScript section (<script>...</script>).Modify the constant that holds the practice text:JavaScript// Change the text here to customize the practice material
const targetText = "asdf jkl; a lad as a lass fall adds ask dad sad flask"; 

// You can replace this with Grade 6 vocabulary, science facts, etc.
Save the file and refresh your browser.🤝 ContributionWe welcome contributions from the community—especially from educators who can suggest new game ideas or improve existing learning content!Ways to ContributeSuggest Content: Submit an issue with lists of relevant vocabulary, common phrases, or ICT terms for existing games.Report Bugs: If you find any issues with the game mechanics or display, please open an issue.Develop New Games: Create a new folder for a new educational game (e.g., a memory game, a programming concept quiz) using HTML, CSS, and JS, and submit a Pull Request.Contribution GuidelinesUse clear and concise code comments.Ensure all HTML files are fully contained (use internal <style> and <script> blocks) for easy deployment.Keep the design responsive so games work well on both desktops and tablets.
