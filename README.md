<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Encouragement for Trem</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
        }
        #clickButton {
            background-color: #ff69b4;
            color: white;
            border: none;
            padding: 20px 40px;
            font-size: 24px;
            cursor: pointer;
            border-radius: 50%;
            transition: all 0.3s ease;
        }
        #clickButton:active {
            background-color: #ff1493;
        }
    </style>
</head>
<body>
    <button id="clickButton">Click Me!</button>

    <script>
        // Create a list of 500 encouraging phrases for Andrew "Trem"
        const phrases = [
            "Andrew, you are stronger than you think. Keep going now!",
            "Trem, every step you take today is a step towards a better future for your daughter! Keep pushing!",
            "Andrew, quitting alcohol is tough, but you are tougher! You've got this, keep fighting!",
            "Trem, your love for your daughter is your greatest strength. Stay sober for her!",
            "Andrew, every day you stay sober, you're becoming the best version of yourself! Keep at it!",
            "Trem, you're a soldier in the streets of Bristol, fighting for a better life. Do not stop now!",
            "Andrew, walking 10 miles a day is no joke! Your body and mind are thanking you! Keep it up!",
            "Trem, you are setting an incredible example for your daughter! She will always be proud of you!",
            "Andrew, the Yankees never give up, and neither do you! Keep swinging for the fences!",
            "Trem, you hustle every day, and your dedication is inspiring! Keep moving forward!",
            "Andrew, sobriety is your power, and you're owning it! Stay strong!",
            "Trem, each day sober is a victory! Keep stacking those wins now!",
            "Andrew, your daughter is lucky to have a dad who works so hard for her! Stay strong, Trem!",
            "Trem, your heart is getting stronger with every step, and so is your resolve! Keep going!",
            "Andrew, you are an absolute warrior. Keep battling for yourself and your family!",
            "Trem, the streets of Bristol can't hold you back. You are a force of positivity! Keep shining!",
            "Andrew, staying sober today means a brighter tomorrow for you and your daughter! Keep pushing!",
            "Trem, you're an MVP every day you choose to stay sober! Keep winning!",
            "Andrew, your hard work as a mailman is keeping you fit and sharp. Keep at it!",
            "Trem, think of every step you take as a step away from alcohol and towards freedom! Keep stepping!",
            "Andrew, your journey inspires others. Never underestimate your strength! Keep moving!",
            "Trem, you are building a legacy for your daughter. She will always look up to you!",
            "Andrew, the Yankees have comebacks, and so do you. You are winning this game!",
            "Trem, you are resilient. Sobriety is just another challenge you're conquering! Keep at it!",
            "Andrew, walking miles every day shows your strength, both inside and out! Keep going!",
            "Trem, the war zone of the underpaid and outraged is no match for your courage! Keep fighting!",
            "Andrew, every step of this journey is for your daughter. You're doing amazing! Keep it up!",
            "Trem, baseball is about patience, just like your journey. Keep swinging!",
            "Andrew, you are not alone in this fight. You've got your own team cheering for you! Keep fighting!",
            "Trem, each day sober is a grand slam! Keep hitting them out of the park!",
            "Andrew, you are more than your struggles. You are an incredible dad and a hard worker! Keep going!",
            "Trem, your perseverance is remarkable. Keep pushing forward, now is the time!",
            "Andrew, your daughter will remember these moments of your strength. Keep showing up!",
            "Trem, the Yankees fight until the end, and so do you! Never give up!",
            "Andrew, you have the heart of a champion. Stay in the game! Keep pushing!",
            "Trem, every mile you walk makes you stronger—body, heart, and soul! Keep it up!",
            "Andrew, you are rewriting your story one sober day at a time! Keep going!",
            "Trem, stay the course. Every day is another victory! Keep fighting!",
            "Andrew, your strength is building a better future for your daughter! Keep moving forward!",
            "Trem, you are proving every day that you are stronger than your past! Keep it up!",
            "Andrew, the streets of Bristol can't break you—you're making them yours! Keep going!",
            "Trem, you are a true warrior, facing every challenge head-on! Stay strong!",
            "Andrew, sobriety is your superpower. Keep using it and move forward!",
            "Trem, every click, every step, every moment is progress. You are unstoppable! Keep going!",
            "Andrew, your daughter’s future is brighter because of your strength today! Keep fighting!",
            "Trem, the Yankees never quit, and neither do you! Stay in the fight!",
            "Andrew, you're walking towards greatness. Keep those feet moving! Don't stop!",
            "Trem, you've already come so far. Keep putting one foot in front of the other! You got this!",
            "Andrew, every mile you walk is a testament to your strength and determination! Keep going!",
            "Trem, you are capable of greatness, and you're showing it every day! Keep moving!",
            "Andrew, you are proving that it's possible to overcome anything! Keep going!",
            "Trem, your daughter sees you as her hero. Keep being that for her! Keep fighting!",
            "Andrew, you are enough, just as you are. Keep fighting for yourself and your family!",
            "Trem, the journey isn't easy, but it's worth it. Keep going!",
            "Andrew, your heart is getting stronger, and so is your spirit! Stay strong!",
            "Trem, you are capable of achieving anything. Keep your eyes on the prize! Don't give up!",
            "Andrew, staying sober today means winning another day for yourself and your daughter! Keep fighting!",
            "Trem, you're not just surviving, you're thriving! Keep it up!",
            "Andrew, the streets may be tough, but you are tougher. Keep hustling!",
            "Trem, baseball is a game of endurance, just like life. Keep playing to win!",
            "Andrew, your hard work and dedication are paying off, one day at a time! Keep at it!",
            "Trem, your daughter believes in you, and so do we. Keep pushing forward!",
            "Andrew, you are setting an incredible example of perseverance and strength! Keep fighting!",
            "Trem, every click is another step towards a better life. Keep going!",
            "Andrew, stay strong, stay focused, stay sober. You've got this!",
            "Trem, your dedication is inspiring. You are an absolute legend! Keep moving forward!",
            "Andrew, the Yankees wouldn't quit, and neither will you! You're winning every day!",
            "Trem, each sober day is a victory worth celebrating! Keep going!",
            "Andrew, you are the hero of your own story. Keep writing it with courage!",
            "Trem, the miles you walk are adding up to something incredible—your best life! Keep going!",
            "Andrew, your strength is unmatched. Keep pushing through!",
            "Trem, you are showing your daughter what true strength looks like. Keep being her hero!",
            "Andrew, every day without alcohol is another day of freedom. You're doing it! Keep fighting!",
            "Trem, the streets of Bristol have nothing on you. You are unstoppable!",
            "Andrew, stay focused on the prize—your health, your happiness, your daughter! Keep at it!",
            "Trem, you are a warrior. Keep fighting the good fight!",
            "Andrew, your love for your daughter is your guiding light. Keep following it!",
            "Trem, the Yankees play to win, and so do you! Keep swinging for the stars!",
            "Andrew, you are building a life that your daughter will be proud of. Keep it up!",
            "Trem, your strength is your superpower. Use it every single day! Keep pushing!",
            "Andrew, you are stronger than any craving. You are in control! Keep going!",
            "Trem, every step is progress. Every day is a victory. Keep moving forward!",
            "Andrew, your daughter looks up to you. You are her hero—keep being that for her!",
            "Trem, you are making strides towards a brighter future. Keep it up!",
            "Andrew, your love for baseball reminds you that practice makes perfect. Keep practicing life!",
            "Trem, you've got the heart of a champion. Keep fighting for your goals!",
            "Andrew, every day you stay sober is another day of winning for you and your daughter!",
            "Trem, the streets of Bristol are tough, but you're tougher! Keep hustling!",
            "Andrew, your strength and dedication inspire everyone around you! Keep going!",
            "Trem, the Yankees never back down, and neither do you. Keep swinging!",
            "Andrew, your daughter is proud of you. Keep giving her more reasons to smile!",
            "Trem, you are an absolute legend in these streets. Keep fighting for your dreams!",
            "Andrew, each sober day is a grand slam! You're knocking it out of the park!",
            "Trem, stay strong, stay steady, stay in the game! You've got this!",
            "Andrew, you are not just a mailman; you're a hero in your own story. Keep believing!",
            "Trem, the miles you walk are building a foundation for a great future! Keep going!",
            "Andrew, your hard work does not go unnoticed. Keep pushing!",
            "Trem, your daughter’s future is brighter because of the strength you're showing today! Keep at it!",
            "Andrew, you are unstoppable. Keep moving forward, no matter what!",
            "Trem, baseball and life both have ups and downs. Keep swinging for the ups!",
            "Andrew, you are courageous. Keep making choices that make you proud!",
            "Trem, the fight is worth it, and you're winning every day. Keep going!",
            "Andrew, your daughter loves you, and she's cheering you on every single day!",
            "Trem, the Yankees fight for every win, just like you! Keep up the hustle!",
            "Andrew, sobriety looks great on you. Keep it up for yourself and your daughter!",
            "Trem, you are a rock for your family. Keep being that strong foundation!",
            "Andrew, every step forward, no matter how small, is a step worth celebrating! Keep going!",
            "Trem, the streets are tough, but you are tougher. Stay strong!",
            "Andrew, each day is another chapter in your comeback story! Keep writing it!",
            "Trem, your love for baseball reminds you to always play the long game. Stay steady!",
            "Andrew, you are a hero to your daughter, and you are her champion every day! Keep at it!",
            "Trem, keep fighting for what matters most—your health, your daughter, and your future!",
            "Andrew, the miles you walk are proof of your dedication. Keep stepping forward!",
            "Trem, you are the champion of your own life. Keep playing to win!",
            "Andrew, you are a true hero. Keep believing in yourself, and never give up!"
        ];

        let clickButton = document.getElementById('clickButton');
        
        // Add click event listener to the button
        clickButton.addEventListener('click', () => {
            // Choose a random phrase each time Trem clicks
            const randomIndex = Math.floor(Math.random() * phrases.length);
            clickButton.innerText = phrases[randomIndex];

            // Make the button move to a random position on the screen
            clickButton.style.position = 'absolute';
            clickButton.style.top = Math.random() * (window.innerHeight - 100) + 'px';
            clickButton.style.left = Math.random() * (window.innerWidth - 100) + 'px';
        });
    </script>
</body>
</html>
