<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Behavior Chart</title>
    <link rel="icon" type="image/png" href="photo.png">
    <link rel="apple-touch-icon" href="photo.png">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="mobile-web-app-capable" content="yes">
    <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Press Start 2P', cursive;
            text-align: center;
            margin: 0;
            padding: 0;
            background-color: #001f3f; /* Dark navy background */
            color: white; /* White text */
        }

        h1 {
            background-color: #003366; /* Slightly lighter navy */
            padding: 20px;
            color: white;
        }

        .class-section {
            margin-top: 30px;
        }

        .class-name {
            font-size: 1.5em;
            margin-bottom: 20px;
            color: #ffcc00; /* Yellow highlight */
        }

        .students-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            grid-gap: 15px;
            justify-items: center;
            margin-top: 20px;
            padding: 20px;
        }

        .student {
            background-color: #00274d; /* Slightly lighter navy */
            padding: 15px;
            border-radius: 10px;
            width: 150px;
        }

        .student-name {
            display: block;
            margin-top: 10px;
            font-size: 0.8em;
        }

        .life-bar {
            display: flex;
            justify-content: center;
            margin-top: 10px;
        }

        .life {
            width: 30px;
            height: 30px;
            margin: 5px;
            background-size: cover;
        }

        .life.deducted {
            opacity: 0.3;
        }

        .button {
            margin-top: 10px;
            padding: 10px 20px;
            background-color: #ff4136; /* Red button */
            color: white;
            border: none;
            cursor: pointer;
            font-size: 0.7em;
            border-radius: 5px;
        }

        .button:active {
            background-color: #d32f2f;
        }

        #students-container {
            margin-top: 30px;
            display: none;
        }

        select {
            padding: 5px;
            font-size: 1em;
            background-color: #00274d;
            color: white;
            border: 1px solid white;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <h1>Game Start</h1>

    <label for="class-select">Select Class:</label>
    <select id="class-select">
        <option value="">--Choose a class--</option>
    </select>

    <div id="students-container" class="students-grid"></div>

    <script>
        const classes = [
            {
                className: 'MAG1',
                students: [
                    { name: 'Hyun Kang', lives: 3 },
                    { name: 'William Baek', lives: 3 },
                    { name: 'Yuju Min', lives: 3 },
                    { name: 'Emma Kim', lives: 3 },
                    { name: 'Ella Ha', lives: 3 },
                    { name: 'Shawn Oh', lives: 3 },
                    { name: 'Min Kim', lives: 3 },
                    { name: 'Jane Lee', lives: 3 },
                    { name: 'Evan Jung', lives: 3 },
                    { name: 'Jenny Yoon', lives: 3 },
                    { name: 'Johann Lee', lives: 3 },
                    { name: 'Emily Joo', lives: 3 }
                ]
            },
            {
                className: 'S1-R',
                students: [
                    { name: 'Irene Song', lives: 3 },
                    { name: 'Roy Myung', lives: 3 },
                    { name: 'Suho Park', lives: 3 },
                    { name: 'Thomas Hong', lives: 3 },
                    { name: 'Estelle Jung', lives: 3 },
                    { name: 'Allie Lee', lives: 3 },
                    { name: 'Irene Jung', lives: 3 },
                    { name: 'Sally Yang', lives: 3 },
                    { name: 'Kevin Park', lives: 3 },
                    { name: 'Evelyn Joo', lives: 3 },
                    { name: 'Jordan Oh', lives: 3 },
                    { name: 'Jenny Kim', lives: 3 }
                ]
            }
        ];

        function populateClassDropdown() {
            const selectElement = document.getElementById("class-select");
            classes.forEach((classData, index) => {
                const option = document.createElement("option");
                option.value = index;
                option.textContent = classData.className;
                selectElement.appendChild(option);
            });
        }

        function showStudents(classIndex) {
            const studentsContainer = document.getElementById("students-container");
            studentsContainer.innerHTML = '';
            const classData = classes[classIndex];

            classData.students.forEach((student, studentIndex) => {
                const studentDiv = document.createElement('div');
                studentDiv.classList.add('student');
                studentDiv.innerHTML = `
                    <span class="student-name">${student.name}</span>
                `;

                const lifeBar = document.createElement('div');
                lifeBar.classList.add('life-bar');
                for (let i = 1; i <= 3; i++) {
                    const life = document.createElement('div');
                    life.classList.add('life');
                    life.id = `life-${classIndex}-${studentIndex}-${i}`;
                    life.style.backgroundImage = 'url("photo.png")';
                    lifeBar.appendChild(life);
                }

                studentDiv.appendChild(lifeBar);

                const deductButton = document.createElement('button');
                deductButton.classList.add('button');
                deductButton.textContent = `Deduct Life`;
                deductButton.onclick = () => deductLife(classIndex, studentIndex);

                const addButton = document.createElement('button');
                addButton.classList.add('button');
                addButton.textContent = `Add Life`;
                addButton.onclick = () => addLife(classIndex, studentIndex);

                studentDiv.appendChild(deductButton);
                studentDiv.appendChild(addButton);

                studentsContainer.appendChild(studentDiv);
            });

            studentsContainer.style.display = 'grid';
        }

        function deductLife(classIndex, studentIndex) {
            const student = classes[classIndex].students[studentIndex];
            if (student.lives > 0) {
                student.lives--;
                updateLifeBar(classIndex, studentIndex);
            } else {
                alert(`No lives left for ${student.name}`);
            }
        }

        function addLife(classIndex, studentIndex) {
            const student = classes[classIndex].students[studentIndex];
            if (student.lives < 3) {
                student.lives++;
                updateLifeBar(classIndex, studentIndex);
            } else {
                alert(`${student.name} already has 3 lives!`);
            }
        }

        function updateLifeBar(classIndex, studentIndex) {
            const student = classes[classIndex].students[studentIndex];
            const hearts = document.querySelectorAll(`#life-${classIndex}-${studentIndex}-1, #life-${classIndex}-${studentIndex}-2, #life-${classIndex}-${studentIndex}-3`);
            hearts.forEach((heart, index) => heart.classList.toggle('deducted', index >= student.lives));
        }

        document.getElementById("class-select").addEventListener("change", function() {
            if (this.value !== "") showStudents(this.value);
        });

        populateClassDropdown();
    </script>
</body>
</html>
