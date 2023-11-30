<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aventura Monstruosa</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-size: cover;
            font-family: 'Arial', sans-serif;
            color: white;
            text-align: center;
            padding-top: 50px;
        }

        .container {
            background: rgba(0, 0, 0, 0.5);
            padding: 20px;
            border-radius: 10px;
            margin: 20px;
        }

        button {
            padding: 15px 30px;
            font-size: 16px;
            margin-top: 20px;
            cursor: pointer;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        button:hover {
            background-color: #45a049;
        }

        .quiz-container {
            display: none;
        }

        .feedback {
            margin-top: 20px;
            font-size: 18px;
        }

        .score-container {
            display: none;
            margin-top: 50px;
        }

        label {
            display: block;
            margin: 10px 0;
        }
    </style>
</head>

<body>
    
<body style="background-image: url('https://p4.wallpaperbetter.com/wallpaper/95/629/184/animated-comedy-dark-fantasy-wallpaper-preview.jpg');">

    <div class="container">
        <h1>¡Hola monstruo!</h1>
        <p>Los adjetivos se utilizan para añadir información a lo que escribimos y expresamos y proporcionar a los lectores e interlocutores una imagen más detallada y completa de un tema.
            proporcionan detalles relevantes que ayudan a la visualización y comprensión de un tema por parte del lector.</p>
           
        <button onclick="startQuiz()">Empezar aventura</button>

    </div>

    <div class="container quiz-container" id="quiz-container">
        <!-- Preguntas y opciones se cargarán dinámicamente aquí -->
    </div>

    <div class="score-container" id="score-container">
        <h1>Tu Puntuación</h1>
        <p id="score-message"></p>
    </div>

    <script>
        let currentQuestion = 0;
        let score = 0;

        const questions = [
            {
                question: "La noche en el Hotel Transilvania era:",
                options: ["Soleada", "Espeluznante", "Radiante", "Alegre", "Tropical"],
                correctAnswer: "Espeluznante",
                background: "https://i.pinimg.com/736x/5f/f2/13/5ff213c9cc4e7fe7b1fe69e6360a6350--dracula.jpg"
            },
            {
                question: "El vampiro Drácula es conocido por ser:",
                options: ["Juguetón", "Malvado", "Encantador", "Brillante", "Feliz"],
                correctAnswer: "Encantador",
                background: "https://m.media-amazon.com/images/M/MV5BMTg0OTIxNzM4OV5BMl5BanBnXkFtZTcwNDkzNTQ5OA@@._V1_QL75_UX500_CR0,47,500,281_.jpg"
            },
            {
                question: "Mavis vestía un vestido:",
                options: ["Deslumbrante", "Aburrido", "Apagado", "Soso", "Desgastado"],
                correctAnswer: "Deslumbrante",
                background: "https://i.pinimg.com/564x/f8/4d/88/f84d88856cd6f9515bcea0ed392bd5c3.jpg"
            },
            {
                question: "La risa del monstruo Frankenstein era:",
                options: ["Melódica", "Estruendosa", "Suave", "Aguda", "Tranquila"],
                correctAnswer: "Estruendosa",
                background: "https://i.pinimg.com/originals/d2/92/b9/d292b9114838a2127e81c97306bb321c.png"
            },
            {
                question: "El Hotel Transilvania estaba rodeado de:",
                options: ["Caos", "Serenidad", "Oscuridad", "Despejado", "Luminoso"],
                correctAnswer: "Oscuridad",
                background: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQEAHL_gLqzIzw9NYrR5JBKz_0YCTUnYJIm2xpX5czv08kxClc51Y90LrIuUpt_9nvngns&usqp=CAU"
            },
            {
                question: "La decoración de la fiesta era:",
                options: ["Apagada", "Deslumbrante", "Normal", "Sencilla", "Monótona"],
                correctAnswer: "Deslumbrante",
                background: "https://i.ytimg.com/vi/a_ku8J5fQUE/maxresdefault.jpg"
            },
            {
                question: "El lobo Wayne era:",
                options: ["Astuto", "Lento", "Torpe", "Despistado", "Inactivo"],
                correctAnswer: "Astuto",
                background: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTNPB3BkDz05LmS_De8D3HcAH0cVXKs3Flni1DTXaahXAO087ZFAtLNdbfGyMvj8Lw8P5s&usqp=CAU"
            },
            {
                question: "La música en el Hotel Transilvania era:",
                options: ["Ensordecedora", "Tranquila", "Aburrida", "Estridente", "Suave"],
                correctAnswer: "Ensordecedora",
                background: "https://i.ytimg.com/vi/d3lvcN0asww/maxresdefault.jpg"
            },
            {
                question: "El personaje Blobby era:",
                options: ["Desorganizado", "Brillante", "Pegajoso", "Hiperactivo", "Inmóvil"],
                correctAnswer: "Pegajoso",
                background: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRkOe1_6fpRig2U3OxpPDiDUDdPRjcFkgAwZA&usqp=CAU"
            },
            {
                question: "La atmosfera en el Hotel Transilvania era:",
                options: ["Relajada", "Tensa", "Desinteresada", "Eufórica", "Insulsa"],
                correctAnswer: "Tensa",
                background: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSF-k_yqal2qkcPGkDIgNqvzsWStoyf6EIF1Q&usqp=CAU"
            },
            {
                question: "La amistad entre Mavis y Jonathan era:",
                options: ["Aterradora", "Encantadora", "Desastrosa", "Caótica"],
                correctAnswer: "Encantadora",
                background: "https://www.agendapop.cl/wp-content/uploads/2017/02/hotel_transylvania-800x445.jpg"
            },
        ];

        function startQuiz() {
            document.body.style.backgroundImage = `url(${questions[currentQuestion].background})`;
            document.querySelector('.container').style.display = 'none';
            document.getElementById('quiz-container').style.display = 'block';
            loadQuestion();
        }

        function loadQuestion() {
            const questionContainer = document.getElementById('quiz-container');
            const currentQuestionData = questions[currentQuestion];
            const optionsHTML = currentQuestionData.options.map((option, index) => {
                return `<label><input type="radio" name="q${currentQuestion}" value="${option}"> ${option}</label>`;
            }).join('');

            questionContainer.innerHTML = `
                <h2>${currentQuestionData.question}</h2>
                ${optionsHTML}
                <button onclick="checkAnswer('${currentQuestionData.correctAnswer}')">Siguiente</button>
                <div id="feedback-q${currentQuestion}" class="feedback"></div>
            `;
        }

        function checkAnswer(correctAnswer) {
            const selectedAnswer = document.querySelector(`input[name=q${currentQuestion}]:checked`);
            const feedback = document.getElementById(`feedback-q${currentQuestion}`);

            if (selectedAnswer) {
                if (selectedAnswer.value === correctAnswer) {
                    feedback.innerHTML = '¡Correcto!';
                    feedback.style.color = 'green';
                    score += 10;
                } else {
                    feedback.innerHTML = 'Incorrecto. ¡Inténtalo de nuevo!';
                    feedback.style.color = 'red';
                }

                selectedAnswer.disabled = true;
                currentQuestion++;

                if (currentQuestion < questions.length) {
                    document.body.style.backgroundImage = `url(${questions[currentQuestion].background})`;
                    loadQuestion();
                } else {
                    showFinalScore();
                }
            } else {
                feedback.innerHTML = 'Por favor, selecciona una respuesta.';
                feedback.style.color = 'red';
            }
        }

        function showFinalScore() {
            const scoreContainer = document.getElementById('score-container');
            const scoreMessage = document.getElementById('score-message');

            scoreContainer.style.display = 'block';

            if (score >= 60) {
                scoreMessage.innerHTML = `¡Felicidades! Has demostrado ser un experto en el uso de adjetivos en el Hotel Transilvania. Tu conocimiento es tan impresionante como las habilidades de Drácula para organizar una fiesta. ¡Sigue así y continúa explorando el fascinante mundo de las palabras! Tu puntuación es: ${score}/100`;
                scoreMessage.style.color = 'green';
            } else {
                scoreMessage.innerHTML = `¡Game Over! Parece que necesitas un poco más de práctica con los adjetivos en el Hotel Transilvania. ¡No te preocupes! Cada error es una oportunidad para aprender. ¡Sigue intentándolo! Tu puntuación es: ${score}/100`;
                scoreMessage.style.color = 'red';
            }
        }
    </script>

</body>

</html>
