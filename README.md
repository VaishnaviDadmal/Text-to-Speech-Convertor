# Text-to-Speech-Convertor
The Text to Speech Converter is a simple and user-friendly web application that reads aloud any text entered by the user. It uses the Web Speech API's SpeechSynthesis interface to convert written text into spoken words.

 Features:
Voice Playback: Instantly converts written text into speech when the button is clicked.

Responsive Design: A fully responsive UI built with HTML, CSS, and JavaScript.

Clean Layout: Visually appealing layout with modern typography and color schemes.

User Interaction: Easy-to-use button and textarea for smooth user experience.

🌐 Technologies Used:
HTML5: For structuring the webpage.

CSS3: For styling and responsive design.

JavaScript (ES6): For integrating the SpeechSynthesisUtterance API, handling events, and converting text to audio.

🧠 How It Works:
The user types or pastes text into the textarea.

On clicking the Listen button, JavaScript fetches the text and passes it to the SpeechSynthesisUtterance object.

The window.speechSynthesis.speak() method is triggered to vocalize the input text.

You can extend this project further by:

Adding multiple voice options to the <select> dropdown.

Letting users adjust speech rate and pitch.

Supporting different languages and dialects.
