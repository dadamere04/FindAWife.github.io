let scores = {
    juli: 0,
    daphenie: 0, //ip
    solana: 0, //done
    liz: 0, //done
    tati: 0, //ip
    makayla: 0, //done
    marie: 0,
    fefe: 0,
    kaya: 0, //pi
    yvonne: 0,
    akua: 0
};

const quizQuestions = [
    { question: "Name", type: "text" },
    {
        question: "Who do you look like most?",
        type: "radio with pics",
        answers: {
            a: { image: "Latinblx spicy white.jpeg", scores: {solana:1, kaya:1} },
            b: { image: "latinblx 2.jpeg", scores: {makayla:1, kaya:1} },
            c: { image: "latinblx 3.jpeg", scores: {solana:1, liz:1, kaya:1} },
            d: { image: "latinblx 4.webp", scores: {makayla:1, kaya:1} },
            e: { image: "latinblx black man.webp", scores: {makayla:1, solana:1, liz:1, daphenie:1, tati:1, kaya:1} },
            f: { image: "latinblx hispanic.jpeg", scores: {solana:1, kaya:1} }
        }
    },
    {
        question: "Which of these most closely relates to your body type?",
        type: "radio with pics",
        answers: {
            a: { image: "skinny.png", scores: {} },
            b: { image: "atheletic.png", scores: {makayla:1, solana:1, daphenie:1, tati:1, kaya:1} },
            c: { image: "3.png", scores: {makayla:1, solana:1, liz:1, daphenie:1, tati:1, kaya:1} },
            d: { image: "4.png", scores: {makayla:1, solana:1, tati:1} },
            e: { image: "5.png", scores: {solana:1} },
            f: { image: "6.png", scores: {solana:1} },
            g: { image: "7.png", scores: {makayla:1, solana:1, liz:1, daphenie:1, tati:1, kaya:1} }
        }
    },
    {
        question: "How tall are you?",
        type: "radio",
        answers: {
            a: { text: "shorter", scores: {} },
            b: { text: "5'0", scores: {} },
            c: { text: "5'1", scores: {} },
            d: { text: "5'2", scores: {} },
            e: { text: "5'3", scores: {} },
            f: { text: "5'4", scores: {} },
            g: { text: "5'5", scores: {} },
            h: { text: "5'6", scores: {} },
            i: { text: "5'7", scores: {} },
            j: { text: "5'8", scores: {daphenie:1} },
            k: { text: "5'9", scores: {solana:1, daphenie:1} },
            l: { text: "5'10", scores: {solana:1, daphenie:1, tati:1, kaya:1} },
            m: { text: "5'11", scores: {solana:1, daphenie:1, tati:1, kaya:1} },
            n: { text: "6'0", scores: {makayla:1, solana:1, daphenie:1, tati:1, kaya:1} },
            o: { text: "6'1", scores: {solana:1, daphenie:1, kaya:1} },
            p: { text: "6'2", scores: {solana:1, daphenie:1, kaya:1} },
            q: { text: "6'3", scores: {solana:1, liz:1, daphenie:1} },
            r: { text: "6'4", scores: {solana:1, liz:1, daphenie:1} },
            s: { text: "6'5", scores: {solana:1, liz:1, daphenie:1} },
            t: { text: "6'6", scores: {liz:1, daphenie:1} },
            u: { text: "6'7", scores: {liz:1, daphenie:1} },
            v: { text: "taller", scores: {liz:1} }
        }
    },
    {
        question: "Where are you from?",
        type: "radio",
        answers: {
            a: { text: "Canada or USA", scores: {makayla:1, solana:1, liz:1, daphenie:1, tati:1, kaya:1} },
            b: { text: "North Africa", scores: {makayla:1, solana:1, liz:1, daphenie:1, kaya:1} },
            c: { text: "South Africa", scores: {makayla:1, solana:1, liz:1, daphenie:1, kaya:1} },
            d: { text: "East Africa", scores: {makayla:1, solana:1, liz:1, daphenie:1, kaya:1} },
            e: { text: "West Africa", scores: {solana:1, liz:1, daphenie:1, kaya:1} },
            f: { text: "Central Africa", scores: {solana:1, liz:1, daphenie:1, kaya:1} },
            g: { text: "South America", scores: {makayla:1, solana:1, kaya:1} },
            h: { text: "Central America or Mexico", scores: {solana:1, kaya:1} },
            i: { text: "The Caribbean (including Spanish speaking nations)", scores: {solana:1, liz:1, kaya:1} },
            j: { text: "Europe", scores: {solana:1, tati:1, kaya:1} },
            k: { text: "Southern Asia", scores: {solana:1, kaya:1} },
            l: { text: "East Asia", scores: {makayla:1, solana:1, kaya:1} }
        }
    },
    {
        question: "How old are you?",
        type: "radio",
        answers: {
            a: { text: "18", scores: {} },
            b: { text: "19", scores: {} },
            c: { text: "20", scores: {solana:1, daphenie:1} },
            d: { text: "21", scores: {solana:1, liz:1, daphenie:1, tati:1, kaya:1} },
            e: { text: "22", scores: {makayla:1, solana:1, liz:1, daphenie:1, tati:1, kaya:1} },
            f: { text: "23", scores: {makayla:1, solana:1, liz:1, daphenie:1, tati:1, kaya:1} },
            g: { text: "24", scores: {makayla:1, solana:1, liz:1, daphenie:1, tati:1} },
            h: { text: "25", scores: {makayla:1, solana:1, liz:1, tati:1} },
            i: { text: "26", scores: {liz:1} },
            j: { text: "27", scores: {liz:1} },
            k: { text: "28", scores: {} },
            l: { text: "29", scores: {} },
            m: { text: "30", scores: {} }
        }
    },
    {
        question: "How often do you work out/get active",
        type: "radio",
        answers: {
            a: { text: "Daily", scores: {} },
            b: { text: "5x a week", scores: {daphenie:1, tati:1} },
            c: { text: "3x a week", scores: {makayla:1, solana:1, liz:1, kaya:1} },
            d: { text: "Never", scores: {} }
        }
    },
    {
        question: "Do you play an instrument?",
        type: "radio",
        answers: {
            a: { text: "Yes", scores: { makayla:1 ,solana:1, liz:1, daphenie:1, kaya:.1} },
            b: { text: "No", scores: {makayla:1, liz:1, daphenie:.5, tati:1, kaya:.5} },
            c: { text: "I'm learning one", scores: {makayla:1, liz:1, daphenie:1, kaya:1} },
            d: { text: "I used to but I have not played in a while", scores: {makayla:1, liz:1, daphenie:1, kaya:1} }
        }
    },
    {
        question: "Can you sing?",
        type: "radio",
        answers: {
            a: { text: "Yes", scores: {makayla:.5, solana:1, liz:.5, daphenie:1} },
            b: { text: "No", scores: {tati:1, kaya:1} },
            c: { text: "I can make a joyful noise", scores: {} },
            d: { text: "I can hold a tune", scores: {makayla:.5, liz:1, daphenie:1 } },
            e: { text: "I am tone deaf", scores: {} }
        }
    },
    {
        question: "What kind of music do you like?",
        type: "checkbox",
        answers: {
            a: { text: "Jazz", scores: {solana:1, daphenie:1, kaya:1} },
            b: { text: "Black Gospel", scores: {makayla:1, solana:1, liz:1, daphenie:1, tati:1, kaya:1} },
            c: { text: "Rap", scores: {makayla:1, solana:1, liz:1, daphenie:1, kaya:1} },
            d: { text: "Hip hop", scores: {makayla:1, solana:1, liz:1, daphenie:1, kaya:1} },
            e: { text: "R&B", scores: {makayla:1, solana:1, liz:1, daphenie:1, tati:1, kaya:1} },
            f: { text: "Lofi", scores: {makayla:1, solana:1, daphenie:1, tati:1} },
            g: { text: "Afro-Beats", scores: {makayla:1, solana:1, liz:1, daphenie:1, tati:1} },
            h: { text: "Reggaeton", scores: {solana:1, daphenie:1} },
            i: { text: "Classical", scores: {makayla:1, solana:1} },
            j: { text: "Reggae", scores: {solana:1} },
            k: { text: "Dancehall", scores: {solana:1} },
            l: { text: "Salsa", scores: {solana:1, daphenie:1} },
            m: { text: "Mariachi", scores: {solana:1} },
            n: { text: "Bachata", scores: {solana:1, daphenie:1} },
            o: { text: "Cumbia", scores: {solana:1} },
            p: { text: "Amapiano", scores: {solana:1, daphenie:1, tati:1} }
        }
    },
    {
        question: "Would you allow secular music in your household?",
        type: "radio",
        answers: {
            a: { text: "Yes", scores: {solana:1, liz:.5, daphenie:5, tati:.5, kaya:1} },
            b: { text: "No", scores: {makayla:1, liz:.5, daphenie:5, tati:.5} },
            c: { text: "Maybe", scores: {liz:1, daphenie:1, tati:1} }
        }
    },
    {
        question: "Can you dance?",
        type: "radio",
        answers: {
            a: { text: "Yes", scores: {makayla:.5, solana:.5, liz:.5, daphenie:1, tati:1, kaya:1} },
            b: { text: "No", scores: {makayla:.5, tati:.5, kaya:.5} },
            c: { text: "I know a few popular dances but I'm not great", scores: {makayla:1, solana:.5, liz:.5, tati:1, kaya:1} },
            e: { text: "I can find the beat", scores: {makayla:1, solana:1, liz:1, tati:1, kaya:1} }
        }
    },
    {
        question: "Are you funny?",
        type: "radio",
        answers: {
            a: { text: "Yes", scores: {makayla:1, solana:1, liz:1, daphenie:1, tati:1, kaya:1} },
            b: { text: "No", scores: {} },
            c: { text: "Some people think so", scores: {} },
            d: { text: "Every now and then I crack a lil joke", scores: {} }
        }
    },
    {
        question: "What type of comedy do you enjoy?",
        type: "checkbox",
        answers: {
            a: { text: "Slapstick comedy", scores: {makayla:1, solana:1, kaya:1} },
            b: { text: "Dark comedy", scores: {makayla:1, kaya:1} },
            c: { text: "Self-deprecating humor", scores: {makayla:1} },
            d: { text: "Situational comedy", scores: {makayla:1, solana:1, liz:1, daphenie:1, tati:1, kaya:1} },
            e: { text: "Parody", scores: {makayla:1} },
            f: { text: "Surreal humor", scores: {makayla:1, solana:1, tati:1} },
            g: { text: "Tragicomedy", scores: {makayla:1, solana:1, daphenie:1} },
            h: { text: "Wordplay comedy", scores: {makayla:1, solana:1} },
            i: { text: "Deadpan comedy", scores: {makayla:1, solana:1, liz:1, daphenie:1, tati:1, kaya:1} },
            j: { text: "Sarcasm", scores: {makayla:1, solana:1, liz:1, daphenie:1, tati:1} }
        }
    },
   //prob gonna remove this one
    /*
    {
        question: "How easily do you laugh?",
        type: "scale",
        answers: {
            a: { text: "Very Easily", scores: {} },
            c: { text: "2", scores: {} },
            d: { text: "3", scores: {} },
            e: { text: "4", scores: {} },
            f: { text: "5", scores: {} },
            g: { text: "6", scores: {} },
            h: { text: "7", scores: {} },
            i: { text: "8", scores: {} },
            j: { text: "9", scores: {} },
            k: { text: "Very Few People are funny to me", scores: {} }
        }
    },*/
    {
        question: "What denomination do you most closely identify with?",
        type: "radio",
        answers: {
            a: { text: "Pentecostal", scores: {makayla:2, solana:1, liz:1, daphenie:2, tati:2, kaya:1} },
            b: { text: "Black Baptist", scores: {makayla:1, solana:1, liz:2, tati:1, kaya:1} },
            c: { text: "Southern Baptist", scores: {makayla:1, solana:1, liz:1, tati:1, kaya:1} },
            d: { text: "Assemblies of God", scores: {makayla:1, solana:1, liz:1, tati:1, kaya:1} },
            e: { text: "Presbyterian", scores: {makayla:1, solana:1, liz:1, tati:1, kaya:2} },
            f: { text: "Methodist", scores: {makayla:1, solana:1, liz:1, tati:1, kaya:1} },
            g: { text: "Anglican", scores: {makayla:1, solana:1, liz:1, tati:1, kaya:1} },
            h: { text: "other/non-denominational", scores: {makayla:1, solana:1, liz:1, tati:1, kaya:1} },
        }
    },
    /*
    {
        question: "Would you want your partner to be the same denomination as you?",
        type: "radio",
        answers: {
            a: { text: "Yes", scores: {makayla:1, solana:.5, liz:5, daphenie:1} },
            b: { text: "No", scores: {makayla:.5, solana:.5, liz:.5} },
            c: { text: "Preferred, but it's okay if she isn’t", scores: {makayla:1, liz:1} },
            d: { text: "Not Preferred, but it's okay if she is", scores: {solana:1} }
        }
    },*/
    {
        question: "Do you expect your partner to be your prayer partner?",
        type: "radio",
        answers: {
            a: { text: "Yes", scores: {makayla:1, solana:1, liz:1, daphenie:1, tati:1, kaya:1} },
            b: { text: "No", scores: {} },
            c: { text: "Preferred, but it's okay if she isn’t", scores: {} },
            d: { text: "Not Preferred, but it's okay if she is", scores: {} }
        }
    },
    {
        question: "Can you cook?",
        type: "radio",
        answers: {
            a: { text: "Yes", scores: {makayla:1, solana:.5, liz:1, daphenie:1, tati:1, kaya:1} },
            b: { text: "No", scores: {solana:.5} }
        }
    },
    {
        question: "Do you expect your partner to be able to cook?",
        type: "radio",
        answers: {
            a: { text: "Yes", scores: {makayla:1, solana:1, liz:1, daphenie:1, tati:1} },
            b: { text: "No", scores: {kaya:1} },
            c: { text: "Preferred, but it's okay if she doesn't", scores: {makayla:1, solana:1, liz:1, kaya:1} },
            d: { text: "Not Preferred, but it's okay if she does", scores: {makayla:1, solana:1, liz:1, kaya:1} },
            e: { text: "I need her to or we will live off of take out and fasting", scores: {makayla:1, solana:1, liz:1} }
        }
    },
    {
        question: "If your partner cannot cook do you expect her to learn?",
        type: "radio",
        answers: {
            a: { text: "Yes", scores: {makayla:1, solana:1, liz:1, daphenie:1, tati:1, kaya:1} },
            b: { text: "No", scores: {} },
            c: { text: "Preferred, but it's okay if she isn’t willing", scores: {kaya:1} },
            d: { text: "Not Preferred, but it's okay if she is willing", scores: {} }
        }
    },
    {
        question: "Do you have a good memory?",
        type: "radio",
        answers: {
            a: { text: "Yes, I remember all the little details", scores: {makayla:1, daphenie:1} },
            b: { text: "Yes, I remember important dates and facts, but other things I tend to forget", scores: {solana:1, liz:1, tati:1, kaya:1} },
            c: { text: "No, I can be forgetful", scores: {} }
        }
    },
    {
        question: "Are you a planner?",
        type: "radio",
        answers: {
            a: { text: "I plan big events months prior and smaller events a week prior", scores: {makayla:1, solana:1, daphenie:1} },
            b: { text: "I have a plan for every day", scores: {tati:1} },
            c: { text: "I just play life by ear", scores: {} },
            d: { text: "I play life by ear but big events need planning", scores: {liz:1, kaya:1} }
        }
    },
    {
        question: "How romantic are you? 1 being not romantic at all and 10 being very romantic",
        type: "scale",
        answers: {
            b: { text: "1", scores: {} },
            c: { text: "2", scores: {} },
            d: { text: "3", scores: {} },
            e: { text: "4", scores: {tati:1} },
            f: { text: "5", scores: {solana:1, tati:2} },
            g: { text: "6", scores: {solana:2, daphenie:1, tati:1} },
            h: { text: "7", scores: {makayla:1, solana:1, liz:1, daphenie:2, kaya:1} },
            i: { text: "8", scores: {makayla:2, liz:2, daphenie:1, kaya:2} },
            j: { text: "9", scores: {makayla:1, liz:1, kaya:1} },
            k: { text: "10", scores: {} }
        }
    },
    {
        question: "Are you submissive(1) or dominant(10)?",
        type: "scale",
        answers: {
            a: { text: "1", scores: {} },
            c: { text: "2", scores: {} },
            d: { text: "3", scores: {} },
            e: { text: "4", scores: {} },
            f: { text: "5", scores: {daphenie:1} },
            g: { text: "6", scores: {liz:1, daphenie:2, kaya:1} },
            h: { text: "7", scores: {solana:1, liz:2, daphenie:1, tati:1, kaya:2} },
            i: { text: "8", scores: {solana:2, liz:1, tati:2, kaya:1} },
            j: { text: "9", scores: {makayla:1, solana:1, tati:1} },
            l: { text: "10", scores: {makayla:2} }
        }
    },
    {
        question: "What are your top 2 love languages to give?",
        type: "checkbox",
        answers: {
            a: { text: "words of affirmation", scores: {solana:1} },
            b: { text: "acts of service", scores: {liz:1, daphenie:1, tati:1} },
            c: { text: "receiving gifts", scores: {makayla:1} },
            d: { text: "quality time", scores: {makayla:1, solana:1, liz:1, daphenie:1, tati:1, kaya:1} },
            e: { text: "physical touch", scores: {solana:1, kaya:1} }
        }
    },
    {
        question: "What are your top 2 love languages to receive?",
        type: "checkbox",
        answers: {
            a: { text: "words of affirmation", scores: {solana:1, daphenie:1} },
            b: { text: "acts of service", scores: {daphenie:1, tati:1} },
            c: { text: "receiving gifts", scores: {liz:1} },
            d: { text: "quality time", scores: {makayla:1, solana:1, liz:1, daphenie:1, tati:1, kaya:1} },
            e: { text: "physical touch", scores: {makayla:1, solana:1, kaya:1} }
        }
    },
    {
        question: "Are you adventurous(1) or a homebody(10)?",
        type: "scale",
        answers: {
            a: { text: "1", scores: {} },
            c: { text: "2", scores: {solana:1} },
            d: { text: "3", scores: {solana:2} },
            e: { text: "4", scores: {makayla:1, solana:1, daphenie:1, kaya:1} },
            f: { text: "5", scores: {makayla:2, daphenie:2, kaya:2} },
            g: { text: "6", scores: {makayla:1, liz:1, daphenie:1, kaya:1} },
            h: { text: "7", scores: {liz:2, tati:1} },
            i: { text: "8", scores: {liz:1, tati:2} },
            j: { text: "9", scores: {tati:1} },
            l: { text: "10", scores: {} }
        }
    },
    {
        question: "Are you a spontaneous(1) or routine(10) person?",
        type: "scale",
        answers: {
            a: { text: "1", scores: {solana:1} },
            c: { text: "2", scores: {solana:2} },
            d: { text: "3", scores: {solana:1, daphenie:1} },
            e: { text: "4", scores: {liz:1, daphenie:2} },
            f: { text: "5", scores: {makayla:1, liz:2, daphenie:1, tati:1, kaya:1} },
            g: { text: "6", scores: {makayla:2,liz:1, tati:2, kaya:2} },
            h: { text: "7", scores: {makayla:1, tati:1, kaya:1} },
            i: { text: "8", scores: {} },
            j: { text: "9", scores: {} },
            l: { text: "10", scores: {} }
        }
    },
    {
        question: "Are you an introvert(1) or extrovert(10)?",
        type: "scale",
        answers: {
            a: { text: "1", scores: {} },
            c: { text: "2", scores: {daphenie:1} },
            d: { text: "3", scores: {daphenie:2} },
            e: { text: "4", scores: {solana:1, daphenie:1, tati:1, kaya:1} },
            f: { text: "5", scores: {solana:2, tati:2, kaya:2} },
            g: { text: "6", scores: {makayla:1, solana:1, tati:1, kaya:1} },
            h: { text: "7", scores: {makayla:2} },
            i: { text: "8", scores: {makayla:1} },
            j: { text: "9", scores: {} },
            l: { text: "10", scores: {} }
        }
    },
    {
        question: "Do you want children?",
        type: "radio",
        answers: {
            a: { text: "Yes", scores: {makayla:1, solana:1, liz:1, daphenie:1, kaya:1} },
            b: { text: "No", scores: {tati:1} },
            c: { text: "Maybe", scores: {} }
        }
    },
    {
        question: "How many children do you want?",
        type: "text",
        answers: {}
    }
];







let currentQuestionIndex = 0;

function startQuiz() {
    document.getElementById('start-page').style.display = 'none';
    document.getElementById('quiz-page').style.display = 'block';
    showQuestion(currentQuestionIndex);
}

function showQuestion(index) {
    const quizContainer = document.getElementById('quiz');
    const currentQuestion = quizQuestions[index];
    let answers = [];

    // Loop through the answers of the current question
    for (let letter in currentQuestion.answers) {
        if (currentQuestion.type === "radio with pics") {
            answers.push(
                `<label class="image-option">
                    <input type="radio" name="question${index}" value="${letter}">
                    <img src="${currentQuestion.answers[letter].image}" alt="Option ${letter}" 
                </label>`
            );
        } else if (currentQuestion.type === "radio") {
            answers.push(
                `<label>
                    <input type="radio" name="question${index}" value="${letter}">
                    ${currentQuestion.answers[letter].text}  
                </label>`
            );
        } else if (currentQuestion.type === "checkbox") {
            answers.push(
                `<label>
                    <input type="checkbox" name="question${index}" value="${letter}">
                    ${currentQuestion.answers[letter].text} 
                </label>`
            );
        }
    else if (currentQuestion.type === "scale") {
            answers.push(
                `<label class="scale-option">
                    <input type="radio" name="question${index}" value="${letter}">
                    <span class="scale-number">${currentQuestion.answers[letter].text}</span>
                </label>`
            );
        }
    }

    // Set the inner HTML of the quiz container
    if (currentQuestion.type === "text") {
        quizContainer.innerHTML = `
            <div class="question">${currentQuestion.question}</div>
            <div class="options">
                <label>
                    <input type="text" name="question${index}">
                </label>
            </div>
        `;
    } else {
        quizContainer.innerHTML = `
            <div class="question">${currentQuestion.question}</div>
            <div class="options">${answers.join('')}</div>
        `;
    }

    updateProgressBar(index);
}


function updateProgressBar(index) {
    const progressBar = document.getElementById('progress-bar');
    const progress = ((index + 1) / quizQuestions.length) * 100;
    progressBar.style.width = progress + '%';
}

function showNextQuestion() {
    const quizContainer = document.getElementById('quiz');
    const currentQuestion = quizQuestions[currentQuestionIndex];
    let isValidAnswer = false;

    if (currentQuestion.type === "text") {
        const userAnswer = quizContainer.querySelector(`input[name="question${currentQuestionIndex}"]`).value.trim();
        isValidAnswer = userAnswer !== '';
    } else if (currentQuestion.type === "checkbox") {
        const userAnswers = quizContainer.querySelectorAll(`input[name="question${currentQuestionIndex}"]:checked`);
        isValidAnswer = userAnswers.length > 0;
        if (isValidAnswer) {
            userAnswers.forEach(answer => {
                let value = answer.value;
                if (currentQuestion.answers[value].scores) {
                    Object.keys(currentQuestion.answers[value].scores).forEach(person => {
                        scores[person] = (scores[person] || 0) + currentQuestion.answers[value].scores[person];
                    });
                }
            });
        }
    } else {
        const userAnswer = quizContainer.querySelector(`input[name="question${currentQuestionIndex}"]:checked`);
        isValidAnswer = userAnswer !== null;
        if (isValidAnswer) {
            let value = userAnswer.value;
            if (currentQuestion.answers[value].scores) {
                Object.keys(currentQuestion.answers[value].scores).forEach(person => {
                    scores[person] = (scores[person] || 0) + currentQuestion.answers[value].scores[person];
                });
            }
        }
    }

    if (isValidAnswer) {
        if (currentQuestionIndex < quizQuestions.length - 1) {
            currentQuestionIndex++;
            showQuestion(currentQuestionIndex);
        } else {
            showResults();
        }
    } else {
        alert('Please select an answer before proceeding.');
    }
}


// Debounce function
function debounce(func, timeout = 300) {
    let timer;
    return (...args) => {
        clearTimeout(timer);
        timer = setTimeout(() => { func.apply(this, args); }, timeout);
    };
}


function showResults() {
    const resultsContainer = document.getElementById('results');
    let sortedPersons = Object.entries(scores).sort((a, b) => b[1] - a[1]); // Sort scores in descending order

    // Create a list of top 3 or fewer if there are fewer participants
    let topResults = sortedPersons.slice(0, 3);

    // Check for ties in the top 3
    let ties = topResults.filter(person => person[1] === topResults[0][1]);

    // Generate descriptions for each top result
    let descriptions = ties.map(person => {
        switch (person[0]) {
            case 'juli': return "Description for Juli";
            case 'daphenie': return "Description for Daph";
            case 'solana': return "Description for Sol";
            case 'liz': return "Description for Liz";
            case 'tati': return "Description for Tati";
            case 'makayla': return "Description for Bibs";
            case 'marie': return "Description for Marie";
            case 'fefe': return "Description for Fefe";
            case 'kaya': return "Description for Kaya";
            case 'yvonne': return "Description for Yvonne";
            case 'akua': return "Description for Akua";
            default: return "No matching personality found.";
        }
    });

    // Prepare HTML content for the results
    let resultsHTML = '';
    ties.forEach((person, index) => {
        resultsHTML += `<div class="result-page">
                            <h2>Your Match is: ${person[0].toUpperCase()}</h2>
                            <p>${descriptions[index]}</p>
                        </div>`;
    });

    // Display results in the results container
    resultsContainer.innerHTML = resultsHTML;
    resultsContainer.style.display = 'block';

    document.getElementById('quiz').style.display = 'none';
    document.getElementById('next').style.display = 'none';
}


document.getElementById('next').addEventListener('click', showNextQuestion);
