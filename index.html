<!DOCTYPE html>
<html>
<head>
    <title>Number Selector</title>
    <style>
        table { border-collapse: collapse; width: 100%; margin-bottom: 20px; }
        th, td { border: 1px solid black; padding: 8px; text-align: center; }
        #generatedsetsTable th:first-child, #generatedsetsTable td:first-child { width: 40%; }

        .highlight { background-color: yellow; }
        .highlight-sum { background-color: lightgreen; }
        .cell-color { background-color: #f2f2f2; font-weight: bold; }
        .number { font-weight: bold; color: white; padding: 10px; cursor: pointer; font-size: 24px; } /* Increased font size */
        /* Color styles for numbers */
        .number:nth-child(1) { background-color: #add8e6; }
        .number:nth-child(2) { background-color: #90ee90; }
        .number:nth-child(3) { background-color: #f5deb3; }
        .number:nth-child(4) { background-color: #ffb6c1; }
        .number:nth-child(5) { background-color: #ffa07a; }
        .number:nth-child(6) { background-color: #ff6699; }
        .number:nth-child(7) { background-color: #f0e68c; }
        .number:nth-child(8) { background-color: #d8bfd8; }
        .number:nth-child(9) { background-color: #dda0dd; }
        .number:nth-child(10) { background-color: #b0e0e6; }
        .number:nth-child(11) { background-color: #afeeee; }
        .number:nth-child(12) { background-color: #98fb98; }
        .number:nth-child(13) { background-color: #ffdead; }
        .number:nth-child(14) { background-color: #ffefd5; }
        .number:nth-child(15) { background-color: #ff9966; }
        .number:nth-child(16) { background-color: #fafad2; }
        .number:nth-child(17) { background-color: #ff6699; }
        .number:nth-child(18) { background-color: #fff0f5; }
        .number:nth-child(19) { background-color: #ffe4b5; }
        .number:nth-child(20) { background-color: #ffe4c4; }
        .number:nth-child(21) { background-color: #ffebcd; }
        .number:nth-child(22) { background-color: #ffe4e1; }
        .number:nth-child(23) { background-color: #ff6699; }
        .number:nth-child(24) { background-color: #fafad2; }
        .number:nth-child(25) { background-color: #ff9966; }
        .number:nth-child(26) { background-color: #ff9966; }
        .number:nth-child(27) { background-color: #f5f5dc; }
        .number:nth-child(28) { background-color: #f5deb3; }
        .number:nth-child(29) { background-color: #ff6699; }
        .number:nth-child(30) { background-color: #f0fff0; }
        .number:nth-child(31) { background-color: #ff6699; }
        .number:nth-child(32) { background-color: #f0e68c; }
        .number:nth-child(33) { background-color: #e6e6fa; }
        .number:nth-child(34) { background-color: #ff9966; }
        .number:nth-child(35) { background-color: #fafad2; }
        .number:nth-child(36) { background-color: #f0e68c; }
        .number:nth-child(37) { background-color: #ff6699; }
        .number:nth-child(38) { background-color: #fff0f5; }
        .number:nth-child(39) { background-color: #ffe4b5; }
        .number:nth-child(40) { background-color: #ffe4c4; }
        .number:nth-child(41) { background-color: #ffebcd; }
        .number:nth-child(42) { background-color: #ffe4e1; }
        .number:nth-child(43) { background-color: #ff9966; }
        .number:nth-child(44) { background-color: #fafad2; }

        /* Slider Styles */
        .slider-container { margin-bottom: 20px; }
    </style>
    <script>
        function initializeNumbers(range) {
            var definitelyWillComeTable = document.getElementById('definitelyWillCome');
            var numbersThatWontComeTable = document.getElementById('numbersThatWontCome');
            definitelyWillComeTable.innerHTML = '';
            numbersThatWontComeTable.innerHTML = ''; // Clear numbers that won't come
            var row = document.createElement('tr');
            definitelyWillComeTable.appendChild(row);
            for (var i = 1; i <= range; i++) {
                var cell = document.createElement('td');
                cell.innerHTML = i;
                cell.className = 'cell-color number';
                cell.style.borderColor = getBorderColor(i); // Set unique border color
                cell.setAttribute('onclick', "moveNumber(" + i + ", 'definitelyWillCome', 'numbersThatWontCome')");
                if (row.cells.length >= 7) {
                    row = document.createElement('tr');
                    definitelyWillComeTable.appendChild(row);
                }
                row.appendChild(cell);
            }
            updateCounts();
            saveNumbersToLocalStorage();
        }

        
        function displayOddNumbers() {
    filterNumbers('odd');
}

function displayEvenNumbers() {
    filterNumbers('even');
}

function displayAllNumbers() {
    filterNumbers('all');
}
function filterNumbers(type) {
   
    var definitelyWillComeTable = document.getElementById('definitelyWillCome');
    var rows = definitelyWillComeTable.getElementsByTagName('tr');
    
    for (var i = 0; i < rows.length; i++) {
        var cells = rows[i].getElementsByTagName('td');
        
        for (var j = 0; j < cells.length; j++) {
            var number = parseInt(cells[j].innerHTML);
            if (type === 'odd' && number % 2 === 0) {
                cells[j].style.display = 'none'; // Hide even numbers
            } else if (type === 'even' && number % 2 !== 0) {
                cells[j].style.display = 'none'; // Hide odd numbers
            } else {
                cells[j].style.display = ''; // Show the numbers
            }
        }
    }
    
    updateCounts(); // Update the counts after filtering
}

        function getBorderColor(number) {
            var colors = ['#ffcc00', '#00ccff', '#ff66ff', '#99ff66', '#ff9933',
                          '#cc66ff', '#66ccff', '#ff6666', '#66ff66', '#ffcc99',
                          '#ccccff', '#ff9900', '#ccff99', '#ff6699', '#66ffcc',
                          '#ff9933', '#33ccff', '#ff66cc', '#99ffcc', '#ffcc33',
                          '#ff99cc', '#ccffcc', '#cc99ff', '#66ffff', '#ff9999',
                          '#66ccff', '#ff6600', '#33cc99', '#cc66cc', '#99ccff',
                          '#ffff66', '#ffcc66', '#ccff33', '#ff6600', '#ccccff',
                          '#99cc99', '#ccff00', '#ffcc99', '#ff9933', '#66ccff',
                          '#ff6666', '#cc99cc'];
            return colors[number - 1] || '#000000'; // Default to black if out of bounds
        }

        function moveNumber(number, fromTableId, toTableId) {
            var fromTable = document.getElementById(fromTableId);
            var toTable = document.getElementById(toTableId);
            var newRow = null;
            for (var i = 0; i < toTable.rows.length; i++) {
                if (toTable.rows[i].cells.length < 7) {
                    newRow = toTable.rows[i];
                    break;
                }
            }
            if (!newRow) {
                newRow = document.createElement('tr');
                toTable.appendChild(newRow);
            }
            var cell = document.createElement('td');
            cell.innerHTML = number;
            cell.className = 'cell-color number';
            cell.style.borderColor = getBorderColor(number); // Maintain border color
            cell.setAttribute('onclick', "moveNumber(" + number + ",'" + toTableId + "','" + fromTableId + "')");
            newRow.appendChild(cell);
            for (var i = 0; i < fromTable.rows.length; i++) {
                for (var j = 0; j < fromTable.rows[i].cells.length; j++) {
                    if (fromTable.rows[i].cells[j].innerHTML == number) {
                        fromTable.rows[i].deleteCell(j);
                        if (fromTable.rows[i].cells.length === 0) {
                            fromTable.deleteRow(i);
                        }
                        break;
                    }
                }
            }
            updateCounts();
            saveNumbersToLocalStorage();
        }

        function saveNumbersToLocalStorage() {
            var definitelyWillComeNumbers = [];
            var definitelyWillComeTable = document.getElementById('definitelyWillCome');
            for (var i = 0; i < definitelyWillComeTable.rows.length; i++) {
                for (var j = 0; j < definitelyWillComeTable.rows[i].cells.length; j++) {
                    definitelyWillComeNumbers.push(definitelyWillComeTable.rows[i].cells[j].innerHTML);
                }
            }
            localStorage.setItem('definitelyWillComeNumbers', JSON.stringify(definitelyWillComeNumbers));

            var numbersThatWontComeNumbers = [];
            var numbersThatWontComeTable = document.getElementById('numbersThatWontCome');
            for (var i = 0; i < numbersThatWontComeTable.rows.length; i++) {
                for (var j = 0; j < numbersThatWontComeTable.rows[i].cells.length; j++) {
                    numbersThatWontComeNumbers.push(numbersThatWontComeTable.rows[i].cells[j].innerHTML);
                }
            }
            localStorage.setItem('numbersThatWontComeNumbers', JSON.stringify(numbersThatWontComeNumbers));
        }

        function populateGeneratedSets() {
            var sets = JSON.parse(localStorage.getItem('generatedSets')) || [];
            var table = document.getElementById('generatedsetsTable');
            table.innerHTML = '<tr><th>Generated Sets</th></tr>';
            for (var i = 0; i < sets.length; i++) {
                var row = document.createElement('tr');
                var cell = document.createElement('td');
                cell.innerHTML = sets[i].join(', ');
                var selectButton = document.createElement('button');
                selectButton.innerHTML = 'Select This Set';
                selectButton.setAttribute('onclick', 'selectGeneratedSet(' + i + ')');
                cell.appendChild(selectButton);
                row.appendChild(cell);
                table.appendChild(row);
            }
        }

        function selectGeneratedSet(index) {
            var sets = JSON.parse(localStorage.getItem('generatedSets')) || [];
            var set = sets[index];
            for (var i = 0; i < set.length; i++) {
                moveNumber(set[i], 'definitelyWillCome', 'numbersThatWontCome');
            }
        }

        function addGeneratedSet() {
            var sets = JSON.parse(localStorage.getItem('generatedSets')) || [];
            var set = [];
            for (var i = 1; i <= 7; i++) {
                var number = parseInt(document.getElementById('number' + i).value, 10);
                if (number && !isNaN(number)) {
                    set.push(number);
                }
            }
            if (set.length === 7) {
                sets.push(set);
                localStorage.setItem('generatedSets', JSON.stringify(sets));
                populateGeneratedSets();
            } else {
                alert('Please enter exactly 7 numbers.');
            }
        }

        window.onload = function() {
            populateGeneratedSets();
            var slider = document.getElementById('numberRangeSlider');
            var rangeValue = parseInt(slider.value, 10);
            initializeNumbers(rangeValue);
            var slider = document.getElementById('numberRangeSlider');
            slider.addEventListener('input', handleSliderChange);
            handleSliderChange(); // Initialize with the slider value
        }

        function loadNumbersFromLocalStorage() {
            var definitelyWillComeNumbers = JSON.parse(localStorage.getItem('definitelyWillComeNumbers')) || [];
            var definitelyWillComeTable = document.getElementById('definitelyWillCome');
            definitelyWillComeTable.innerHTML = '';
            var row = document.createElement('tr');
            definitelyWillComeTable.appendChild(row);
            definitelyWillComeNumbers.forEach(function (number) {
                var cell = document.createElement('td');
                cell.innerHTML = number;
                cell.className = 'cell-color number';
                cell.style.borderColor = getBorderColor(number); // Maintain border color
                cell.setAttribute('onclick', "moveNumber(" + number + ", 'definitelyWillCome', 'numbersThatWontCome')");
                if (row.cells.length >= 7) {
                    row = document.createElement('tr');
                    definitelyWillComeTable.appendChild(row);
                }
                row.appendChild(cell);
            });

            var numbersThatWontComeNumbers = JSON.parse(localStorage.getItem('numbersThatWontComeNumbers')) || [];
            var numbersThatWontComeTable = document.getElementById('numbersThatWontCome');
            numbersThatWontComeTable.innerHTML = '';
            row = document.createElement('tr');
            numbersThatWontComeTable.appendChild(row);
            numbersThatWontComeNumbers.forEach(function (number) {
                var cell = document.createElement('td');
                cell.innerHTML = number;
                cell.className = 'cell-color number';
                cell.style.borderColor = getBorderColor(number); // Maintain border color
                cell.setAttribute('onclick', "moveNumber(" + number + ", 'numbersThatWontCome', 'definitelyWillCome')");
                if (row.cells.length >= 7) {
                    row = document.createElement('tr');
                    numbersThatWontComeTable.appendChild(row);
                }
                row.appendChild(cell);
            });

            updateCounts();
        }

   

        function generateSets() {
            var luckyNumbers = document.getElementById('luckyNumbers').value.split(',').map(Number).filter(Boolean);
            var definitelyWillComeNumbers = JSON.parse(localStorage.getItem('definitelyWillComeNumbers')).map(Number);
            var combinedNumbers = definitelyWillComeNumbers.concat(luckyNumbers);
            var sets = [];
            for (var i = 0; i < 10; i++) {
                var set = [];
                while (set.length < 7) {
                    var number = combinedNumbers[Math.floor(Math.random() * combinedNumbers.length)];
                    if (set.indexOf(number) === -1) {
                        set.push(number);
                    }
                }
                sets.push(set);
            }
            displayGeneratedSets(sets);
        }

        function displayGeneratedSets(sets) {
    var table = document.getElementById('generatedsetsTable');
    table.innerHTML = ''; // Clear existing content
    var header = '<tr><th>Set</th><th>Sum</th><th>Double Digit Sum</th><th>Single Digit Sum</th><th>Multiplication Value</th><th>Multiplication Digit Sum</th><th>Single Digit Multiplication Digit Sum</th><th>Sum of Digit Multiplication Digit Sum</th><th>Matching Lucky Numbers</th></tr>';
    table.innerHTML = header;
    sets.forEach(function(set) {
        var sum = set.reduce((a, b) => a + b, 0);
        var doubleDigitSum = sum.toString().split('').reduce((a, b) => a + parseInt(b), 0);
        var singleDigitSum = doubleDigitSum.toString().split('').reduce((a, b) => a + parseInt(b), 0);
        var multiplicationValue = set.reduce((a, b) => a * b, 1);
        var multiplicationDigitSum = multiplicationValue.toString().split('').reduce((a, b) => a + parseInt(b), 0);
        var singleDigitMultiplicationDigitSum = multiplicationDigitSum.toString().split('').reduce((a, b) => a + parseInt(b), 0);
        var sumOfDigitMultiplicationDigitSum = multiplicationValue.toString().split('').reduce((a, b) => a + parseInt(b), 0);
        var matchingLuckyNumbers = set.filter(number => {
            return document.getElementById('luckyNumbers').value.split(',').map(Number).includes(number);
        });

        var row = table.insertRow();
        row.insertCell().innerHTML = set.join(', ');
        row.insertCell().innerHTML = sum;
        row.insertCell().innerHTML = doubleDigitSum;
        row.insertCell().innerHTML = singleDigitSum;
        row.insertCell().innerHTML = multiplicationValue;
        row.insertCell().innerHTML = multiplicationDigitSum;
        row.insertCell().innerHTML = singleDigitMultiplicationDigitSum;
        row.insertCell().innerHTML = sumOfDigitMultiplicationDigitSum;
        var matchingCell = row.insertCell();
        matchingCell.innerHTML = matchingLuckyNumbers.length;
        matchingLuckyNumbers.forEach(function(number) {
            var span = document.createElement('span');
            span.textContent = number;
            span.className = 'cell-color number';
            span.style.borderColor = getBorderColor(number); // Apply border color
            matchingCell.appendChild(span);
        });
    });
}


        function initializeFromScratch() {
            localStorage.removeItem('definitelyWillComeNumbers');
            localStorage.removeItem('numbersThatWontComeNumbers');
            var slider = document.getElementById('numberRangeSlider');
            var rangeValue = parseInt(slider.value, 10);
            initializeNumbers(rangeValue);
        }

        function updateCounts() {
            var definitelyWillComeTable = document.getElementById('definitelyWillCome');
            var numbersThatWontComeTable = document.getElementById('numbersThatWontCome');
            var countWillCome = 0;
            var countWontCome = 0;
            for (var i = 0; i < definitelyWillComeTable.rows.length; i++) {
                countWillCome += definitelyWillComeTable.rows[i].cells.length;
            }
            for (var i = 0; i < numbersThatWontComeTable.rows.length; i++) {
                countWontCome += numbersThatWontComeTable.rows[i].cells.length;
            }
            document.getElementById('countWillCome').innerHTML = countWillCome;
            document.getElementById('countWontCome').innerHTML = countWontCome;
        }

        

        window.onload = function () {
            loadNumbersFromLocalStorage();
        }
    </script>
</head>
<body>
    <div class="slider-container">
        <label for="numberRangeSlider">Select Number Range (1-44):</label>
        <input type="range" id="numberRangeSlider" min="1" max="44" value="44" onchange="initializeNumbers(this.value)">
    </div>
    <button onclick="initializeFromScratch()">Initialize from Scratch</button>
    <button onclick="displayOddNumbers()">Display Only Odd Numbers</button>
    <button onclick="displayEvenNumbers()">Display Only Even Numbers</button>
    <button onclick="displayAllNumbers()">Display All Numbers</button>

    <h3>Definitely Will Come (<span id="countWillCome">0</span>)</h3>
    <table id="definitelyWillCome"></table>

    <h3>Numbers That Won't Come (<span id="countWontCome">0</span>)</h3>
    <table id="numbersThatWontCome"></table>
    <br/>

    <button onclick="initializeFromScratch()">Initialize from Scratch</button>

    <h2>Lucky Numbers</h2>
    <textarea id="luckyNumbers" rows="4" cols="50"></textarea>
    <button onclick="document.getElementById('luckyNumbers').value=''; saveNumbersToLocalStorage();">Clear</button>

    <button onclick="generateSets()">Generate Sets</button>
    <button onclick="resetNumbers()">Reset</button>

    <h2>Generated Sets</h2>
    <table id="generatedsetsTable"></table>



</body>
</html>
