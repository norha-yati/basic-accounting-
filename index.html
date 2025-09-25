<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Accounting Games for Students</title>
    <style>
        body {
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .header {
            text-align: center;
            color: white;
            margin-bottom: 40px;
        }

        .header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .header p {
            font-size: 1.2rem;
            opacity: 0.9;
        }

        .games-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 30px;
            margin-bottom: 40px;
        }

        .game-card {
            background: white;
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            cursor: pointer;
        }

        .game-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 40px rgba(0,0,0,0.3);
        }

        .game-card h3 {
            color: #4a5568;
            font-size: 1.5rem;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .game-card p {
            color: #718096;
            margin-bottom: 20px;
            line-height: 1.6;
        }

        .play-btn {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            border: none;
            padding: 12px 24px;
            border-radius: 8px;
            font-size: 1rem;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
            width: 100%;
        }

        .play-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(102, 126, 234, 0.4);
        }

        .game-modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.8);
            z-index: 1000;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .modal-content {
            background: white;
            border-radius: 15px;
            padding: 30px;
            max-width: 600px;
            width: 100%;
            max-height: 80vh;
            overflow-y: auto;
            position: relative;
        }

        .close-btn {
            position: absolute;
            top: 15px;
            right: 20px;
            background: none;
            border: none;
            font-size: 24px;
            cursor: pointer;
            color: #718096;
        }

        .question {
            background: #f7fafc;
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
        }

        .options {
            display: grid;
            gap: 10px;
            margin: 15px 0;
        }

        .option {
            background: #edf2f7;
            border: 2px solid transparent;
            padding: 15px;
            border-radius: 8px;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .option:hover {
            background: #e2e8f0;
            border-color: #667eea;
        }

        .option.correct {
            background: #c6f6d5;
            border-color: #38a169;
        }

        .option.incorrect {
            background: #fed7d7;
            border-color: #e53e3e;
        }

        .score {
            text-align: center;
            font-size: 1.2rem;
            font-weight: 600;
            color: #4a5568;
            margin: 20px 0;
        }

        .journal-entry {
            background: #f7fafc;
            border: 1px solid #e2e8f0;
            border-radius: 8px;
            padding: 15px;
            margin: 10px 0;
        }

        .journal-row {
            display: grid;
            grid-template-columns: 2fr 1fr 1fr;
            gap: 10px;
            align-items: center;
            margin: 5px 0;
        }

        .journal-input {
            padding: 8px;
            border: 1px solid #cbd5e0;
            border-radius: 4px;
            font-size: 0.9rem;
        }

        .debit-credit {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 10px;
        }

        @media (max-width: 768px) {
            .games-grid {
                grid-template-columns: 1fr;
            }
            
            .header h1 {
                font-size: 2rem;
            }
            
            .modal-content {
                margin: 10px;
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>🎓 Accounting Games Hub</h1>
            <p>Master the fundamentals of accounting through interactive games!</p>
        </div>

        <div class="games-grid">
            <div class="game-card" onclick="openGame('equation')">
                <h3>⚖️ Accounting Equation Challenge</h3>
                <p>Test your understanding of Assets = Liabilities + Equity with real business scenarios.</p>
                <button class="play-btn">Play Now</button>
            </div>

            <div class="game-card" onclick="openGame('journal')">
                <h3>📝 Journal Entry Master</h3>
                <p>Practice creating proper journal entries for common business transactions.</p>
                <button class="play-btn">Play Now</button>
            </div>

            <div class="game-card" onclick="openGame('classification')">
                <h3>🗂️ Account Classification Quiz</h3>
                <p>Classify accounts into Assets, Liabilities, Equity, Revenue, or Expenses.</p>
                <button class="play-btn">Play Now</button>
            </div>

            <div class="game-card" onclick="openGame('debitcredit')">
                <h3>💰 Debit or Credit Game</h3>
                <p>Master the rules of debits and credits with interactive scenarios.</p>
                <button class="play-btn">Play Now</button>
            </div>
        </div>
    </div>

    <!-- Accounting Equation Game Modal -->
    <div id="equationModal" class="game-modal">
        <div class="modal-content">
            <button class="close-btn" onclick="closeGame()">&times;</button>
            <h2>⚖️ Accounting Equation Challenge</h2>
            <div class="score">Score: <span id="equationScore">0</span>/5</div>
            <div id="equationGame">
                <div class="question">
                    <h4 id="equationQuestion">Loading...</h4>
                    <div class="options" id="equationOptions"></div>
                </div>
                <button class="play-btn" onclick="nextEquationQuestion()" id="equationNext" style="display:none;">Next Question</button>
            </div>
        </div>
    </div>

    <!-- Journal Entry Game Modal -->
    <div id="journalModal" class="game-modal">
        <div class="modal-content">
            <button class="close-btn" onclick="closeGame()">&times;</button>
            <h2>📝 Journal Entry Master</h2>
            <div class="score">Score: <span id="journalScore">0</span>/3</div>
            <div id="journalGame">
                <div class="question">
                    <h4 id="journalQuestion">Loading...</h4>
                    <div class="journal-entry">
                        <div class="journal-row">
                            <strong>Account</strong>
                            <strong>Debit</strong>
                            <strong>Credit</strong>
                        </div>
                        <div id="journalEntries"></div>
                    </div>
                    <button class="play-btn" onclick="checkJournalEntry()" id="journalCheck">Check Answer</button>
                    <button class="play-btn" onclick="nextJournalQuestion()" id="journalNext" style="display:none;">Next Question</button>
                </div>
            </div>
        </div>
    </div>

    <!-- Classification Game Modal -->
    <div id="classificationModal" class="game-modal">
        <div class="modal-content">
            <button class="close-btn" onclick="closeGame()">&times;</button>
            <h2>🗂️ Account Classification Quiz</h2>
            <div class="score">Score: <span id="classificationScore">0</span>/8</div>
            <div id="classificationGame">
                <div class="question">
                    <h4 id="classificationQuestion">Loading...</h4>
                    <div class="options" id="classificationOptions"></div>
                </div>
                <button class="play-btn" onclick="nextClassificationQuestion()" id="classificationNext" style="display:none;">Next Question</button>
            </div>
        </div>
    </div>

    <!-- Debit Credit Game Modal -->
    <div id="debitcreditModal" class="game-modal">
        <div class="modal-content">
            <button class="close-btn" onclick="closeGame()">&times;</button>
            <h2>💰 Debit or Credit Game</h2>
            <div class="score">Score: <span id="debitcreditScore">0</span>/6</div>
            <div id="debitcreditGame">
                <div class="question">
                    <h4 id="debitcreditQuestion">Loading...</h4>
                    <div class="options" id="debitcreditOptions"></div>
                </div>
                <button class="play-btn" onclick="nextDebitCreditQuestion()" id="debitcreditNext" style="display:none;">Next Question</button>
            </div>
        </div>
    </div>

    <script>
        // Game data
        const equationQuestions = [
            {
                question: "A company purchases equipment for $10,000 cash. How does this affect the accounting equation?",
                options: [
                    "Assets increase $10,000, Assets decrease $10,000",
                    "Assets increase $10,000, Liabilities increase $10,000", 
                    "Assets decrease $10,000, Equity decreases $10,000",
                    "No effect on the equation"
                ],
                correct: 0
            },
            {
                question: "A business takes out a $5,000 loan from the bank. What happens?",
                options: [
                    "Assets increase $5,000, Equity increases $5,000",
                    "Assets increase $5,000, Liabilities increase $5,000",
                    "Liabilities increase $5,000, Equity decreases $5,000",
                    "Assets decrease $5,000, Liabilities decrease $5,000"
                ],
                correct: 1
            },
            {
                question: "The owner invests $15,000 cash into the business. The effect is:",
                options: [
                    "Assets increase $15,000, Liabilities increase $15,000",
                    "Assets increase $15,000, Equity increases $15,000",
                    "Assets decrease $15,000, Equity decreases $15,000",
                    "Liabilities decrease $15,000, Equity increases $15,000"
                ],
                correct: 1
            },
            {
                question: "The company pays $2,000 to reduce accounts payable. What occurs?",
                options: [
                    "Assets decrease $2,000, Liabilities decrease $2,000",
                    "Assets increase $2,000, Liabilities increase $2,000",
                    "Assets decrease $2,000, Equity decreases $2,000",
                    "Liabilities decrease $2,000, Equity increases $2,000"
                ],
                correct: 0
            },
            {
                question: "A business earns $3,000 in service revenue (cash). The impact is:",
                options: [
                    "Assets increase $3,000, Liabilities increase $3,000",
                    "Assets increase $3,000, Equity increases $3,000",
                    "Assets decrease $3,000, Equity decreases $3,000",
                    "Liabilities decrease $3,000, Equity increases $3,000"
                ],
                correct: 1
            }
        ];

        const journalQuestions = [
            {
                question: "Record the journal entry: Company purchases office supplies for $500 cash.",
                entries: [
                    { account: "Office Supplies", debit: "500", credit: "" },
                    { account: "Cash", debit: "", credit: "500" }
                ]
            },
            {
                question: "Record the journal entry: Company provides services to customers for $2,000 on account.",
                entries: [
                    { account: "Accounts Receivable", debit: "2000", credit: "" },
                    { account: "Service Revenue", debit: "", credit: "2000" }
                ]
            },
            {
                question: "Record the journal entry: Company pays $800 for monthly rent expense.",
                entries: [
                    { account: "Rent Expense", debit: "800", credit: "" },
                    { account: "Cash", debit: "", credit: "800" }
                ]
            }
        ];

        const classificationQuestions = [
            { question: "Cash", correct: "Asset" },
            { question: "Accounts Payable", correct: "Liability" },
            { question: "Owner's Capital", correct: "Equity" },
            { question: "Service Revenue", correct: "Revenue" },
            { question: "Rent Expense", correct: "Expense" },
            { question: "Equipment", correct: "Asset" },
            { question: "Notes Payable", correct: "Liability" },
            { question: "Salary Expense", correct: "Expense" }
        ];

        const debitCreditQuestions = [
            {
                question: "To increase Cash (an asset account), you would:",
                options: ["Debit Cash", "Credit Cash"],
                correct: 0
            },
            {
                question: "To increase Accounts Payable (a liability account), you would:",
                options: ["Debit Accounts Payable", "Credit Accounts Payable"],
                correct: 1
            },
            {
                question: "To record an expense, you would:",
                options: ["Debit the expense account", "Credit the expense account"],
                correct: 0
            },
            {
                question: "To increase Service Revenue, you would:",
                options: ["Debit Service Revenue", "Credit Service Revenue"],
                correct: 1
            },
            {
                question: "To decrease Equipment (an asset), you would:",
                options: ["Debit Equipment", "Credit Equipment"],
                correct: 1
            },
            {
                question: "To increase Owner's Equity, you would:",
                options: ["Debit Owner's Equity", "Credit Owner's Equity"],
                correct: 1
            }
        ];

        // Game state
        let currentGame = '';
        let currentQuestion = 0;
        let scores = {
            equation: 0,
            journal: 0,
            classification: 0,
            debitcredit: 0
        };

        function openGame(gameType) {
            currentGame = gameType;
            currentQuestion = 0;
            scores[gameType] = 0;
            
            document.getElementById(gameType + 'Modal').style.display = 'flex';
            
            switch(gameType) {
                case 'equation':
                    startEquationGame();
                    break;
                case 'journal':
                    startJournalGame();
                    break;
                case 'classification':
                    startClassificationGame();
                    break;
                case 'debitcredit':
                    startDebitCreditGame();
                    break;
            }
        }

        function closeGame() {
            document.querySelectorAll('.game-modal').forEach(modal => {
                modal.style.display = 'none';
            });
        }

        // Equation Game
        function startEquationGame() {
            document.getElementById('equationScore').textContent = '0';
            showEquationQuestion();
        }

        function showEquationQuestion() {
            const question = equationQuestions[currentQuestion];
            document.getElementById('equationQuestion').textContent = question.question;
            
            const optionsDiv = document.getElementById('equationOptions');
            optionsDiv.innerHTML = '';
            
            question.options.forEach((option, index) => {
                const optionDiv = document.createElement('div');
                optionDiv.className = 'option';
                optionDiv.textContent = option;
                optionDiv.onclick = () => selectEquationAnswer(index);
                optionsDiv.appendChild(optionDiv);
            });
            
            document.getElementById('equationNext').style.display = 'none';
        }

        function selectEquationAnswer(selectedIndex) {
            const question = equationQuestions[currentQuestion];
            const options = document.querySelectorAll('#equationOptions .option');
            
            options.forEach((option, index) => {
                if (index === question.correct) {
                    option.classList.add('correct');
                } else if (index === selectedIndex && index !== question.correct) {
                    option.classList.add('incorrect');
                }
                option.onclick = null;
            });
            
            if (selectedIndex === question.correct) {
                scores.equation++;
                document.getElementById('equationScore').textContent = scores.equation;
            }
            
            document.getElementById('equationNext').style.display = 'block';
        }

        function nextEquationQuestion() {
            currentQuestion++;
            if (currentQuestion < equationQuestions.length) {
                showEquationQuestion();
            } else {
                showGameComplete('equation', scores.equation, equationQuestions.length);
            }
        }

        // Journal Game
        function startJournalGame() {
            document.getElementById('journalScore').textContent = '0';
            showJournalQuestion();
        }

        function showJournalQuestion() {
            const question = journalQuestions[currentQuestion];
            document.getElementById('journalQuestion').textContent = question.question;
            
            const entriesDiv = document.getElementById('journalEntries');
            entriesDiv.innerHTML = '';
            
            question.entries.forEach((entry, index) => {
                const rowDiv = document.createElement('div');
                rowDiv.className = 'journal-row';
                rowDiv.innerHTML = `
                    <input type="text" class="journal-input" placeholder="Account name" data-field="account" data-index="${index}">
                    <input type="number" class="journal-input" placeholder="0" data-field="debit" data-index="${index}">
                    <input type="number" class="journal-input" placeholder="0" data-field="credit" data-index="${index}">
                `;
                entriesDiv.appendChild(rowDiv);
            });
            
            document.getElementById('journalCheck').style.display = 'block';
            document.getElementById('journalNext').style.display = 'none';
        }

        function checkJournalEntry() {
            const question = journalQuestions[currentQuestion];
            const inputs = document.querySelectorAll('#journalEntries .journal-input');
            let correct = true;
            
            inputs.forEach(input => {
                const index = parseInt(input.dataset.index);
                const field = input.dataset.field;
                const expectedValue = question.entries[index][field];
                const actualValue = input.value.trim();
                
                if (field === 'account') {
                    if (actualValue.toLowerCase() !== expectedValue.toLowerCase()) {
                        correct = false;
                        input.style.borderColor = '#e53e3e';
                    } else {
                        input.style.borderColor = '#38a169';
                    }
                } else {
                    if (actualValue !== expectedValue) {
                        correct = false;
                        input.style.borderColor = '#e53e3e';
                    } else {
                        input.style.borderColor = '#38a169';
                    }
                }
            });
            
            if (correct) {
                scores.journal++;
                document.getElementById('journalScore').textContent = scores.journal;
            }
            
            document.getElementById('journalCheck').style.display = 'none';
            document.getElementById('journalNext').style.display = 'block';
        }

        function nextJournalQuestion() {
            currentQuestion++;
            if (currentQuestion < journalQuestions.length) {
                showJournalQuestion();
            } else {
                showGameComplete('journal', scores.journal, journalQuestions.length);
            }
        }

        // Classification Game
        function startClassificationGame() {
            document.getElementById('classificationScore').textContent = '0';
            showClassificationQuestion();
        }

        function showClassificationQuestion() {
            const question = classificationQuestions[currentQuestion];
            document.getElementById('classificationQuestion').textContent = `Classify: ${question.question}`;
            
            const optionsDiv = document.getElementById('classificationOptions');
            optionsDiv.innerHTML = '';
            
            const options = ['Asset', 'Liability', 'Equity', 'Revenue', 'Expense'];
            options.forEach((option, index) => {
                const optionDiv = document.createElement('div');
                optionDiv.className = 'option';
                optionDiv.textContent = option;
                optionDiv.onclick = () => selectClassificationAnswer(option);
                optionsDiv.appendChild(optionDiv);
            });
            
            document.getElementById('classificationNext').style.display = 'none';
        }

        function selectClassificationAnswer(selectedAnswer) {
            const question = classificationQuestions[currentQuestion];
            const options = document.querySelectorAll('#classificationOptions .option');
            
            options.forEach(option => {
                if (option.textContent === question.correct) {
                    option.classList.add('correct');
                } else if (option.textContent === selectedAnswer && selectedAnswer !== question.correct) {
                    option.classList.add('incorrect');
                }
                option.onclick = null;
            });
            
            if (selectedAnswer === question.correct) {
                scores.classification++;
                document.getElementById('classificationScore').textContent = scores.classification;
            }
            
            document.getElementById('classificationNext').style.display = 'block';
        }

        function nextClassificationQuestion() {
            currentQuestion++;
            if (currentQuestion < classificationQuestions.length) {
                showClassificationQuestion();
            } else {
                showGameComplete('classification', scores.classification, classificationQuestions.length);
            }
        }

        // Debit Credit Game
        function startDebitCreditGame() {
            document.getElementById('debitcreditScore').textContent = '0';
            showDebitCreditQuestion();
        }

        function showDebitCreditQuestion() {
            const question = debitCreditQuestions[currentQuestion];
            document.getElementById('debitcreditQuestion').textContent = question.question;
            
            const optionsDiv = document.getElementById('debitcreditOptions');
            optionsDiv.innerHTML = '';
            
            question.options.forEach((option, index) => {
                const optionDiv = document.createElement('div');
                optionDiv.className = 'option';
                optionDiv.textContent = option;
                optionDiv.onclick = () => selectDebitCreditAnswer(index);
                optionsDiv.appendChild(optionDiv);
            });
            
            document.getElementById('debitcreditNext').style.display = 'none';
        }

        function selectDebitCreditAnswer(selectedIndex) {
            const question = debitCreditQuestions[currentQuestion];
            const options = document.querySelectorAll('#debitcreditOptions .option');
            
            options.forEach((option, index) => {
                if (index === question.correct) {
                    option.classList.add('correct');
                } else if (index === selectedIndex && index !== question.correct) {
                    option.classList.add('incorrect');
                }
                option.onclick = null;
            });
            
            if (selectedIndex === question.correct) {
                scores.debitcredit++;
                document.getElementById('debitcreditScore').textContent = scores.debitcredit;
            }
            
            document.getElementById('debitcreditNext').style.display = 'block';
        }

        function nextDebitCreditQuestion() {
            currentQuestion++;
            if (currentQuestion < debitCreditQuestions.length) {
                showDebitCreditQuestion();
            } else {
                showGameComplete('debitcredit', scores.debitcredit, debitCreditQuestions.length);
            }
        }

        function showGameComplete(gameType, score, total) {
            const percentage = Math.round((score / total) * 100);
            let message = '';
            
            if (percentage >= 80) {
                message = '🎉 Excellent work! You\'ve mastered this concept!';
            } else if (percentage >= 60) {
                message = '👍 Good job! Review the missed questions and try again.';
            } else {
                message = '📚 Keep studying! Practice makes perfect in accounting.';
            }
            
            const modalContent = document.querySelector(`#${gameType}Modal .modal-content`);
            modalContent.innerHTML = `
                <button class="close-btn" onclick="closeGame()">&times;</button>
                <div style="text-align: center; padding: 40px 20px;">
                    <h2>Game Complete!</h2>
                    <div style="font-size: 3rem; margin: 20px 0;">
                        ${percentage >= 80 ? '🏆' : percentage >= 60 ? '🎯' : '📖'}
                    </div>
                    <div style="font-size: 2rem; font-weight: bold; color: #667eea; margin: 20px 0;">
                        ${score}/${total} (${percentage}%)
                    </div>
                    <p style="font-size: 1.2rem; color: #4a5568; margin: 20px 0;">${message}</p>
                    <button class="play-btn" onclick="openGame('${gameType}')" style="margin: 10px;">Play Again</button>
                    <button class="play-btn" onclick="closeGame()" style="margin: 10px; background: #718096;">Close</button>
                </div>
            `;
        }
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9847bd9e510be708',t:'MTc1ODc3NDE0OS4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
