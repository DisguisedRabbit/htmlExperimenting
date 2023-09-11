    function openModal(x) {
        document.getElementById(x).style.display = "block";
    }

    function closeModal(x) {
        document.getElementById(x).style.display = "none";
    }

    document.getElementsByClassName("close").onclick = function() {
    closeModal("numberWarning");
    }

    window.onclick = function(event) {
    if (event.target == document.getElementById("numberWarning")) {
        closeModal("numberWarning");
    }
    }
    function print(x){
        console.log(x);
    }
    function clearResult(){
        document.getElementById("result").value = null
    }
    function clearNumbers(){
        document.getElementById("num1").value = null
        document.getElementById("num2").value = null
        clearResult();
    }
    function green(){
        var button = document.getElementsByClassName("clicked")
        for (let index = 0; index < button.length; index++) {
            button[index].classList.remove("clicked")
        }

    }
    function colorchange(x){
        var button = document.getElementById(x);
			button.classList.add("clicked");
    }
// math functions
    function add() {
        const num1 = Number(document.getElementById("num1").value);
        const num2 = Number(document.getElementById("num2").value);
        if (num1 != "" && num2 != "") {
        const result = num1 + num2;
        document.getElementById("result").value = result;
        colorchange('Add');
        } else {
            openModal("numberWarning");
        }
    }

    function subtract() {
        const num1 = Number(document.getElementById("num1").value);
        const num2 = Number(document.getElementById("num2").value);
        if (num1 != "" && num2 != "") {
            const result = num1 - num2;
            document.getElementById("result").value = result;
            colorchange('Subtract');
            } else {
                openModal("numberWarning");
            }
    }

    function multiply() {
        const num1 = Number(document.getElementById("num1").value);
        const num2 = Number(document.getElementById("num2").value);
        if (num1 != "" && num2 != "") {
            const result = num1 * num2;
            document.getElementById("result").value = result;
            colorchange('Multiply');
            } else {
                openModal("numberWarning");
            }
    }

    function divide() {
        const num1 = Number(document.getElementById("num1").value);
        const num2 = Number(document.getElementById("num2").value);
        if (num1 != "" && num2 != "") {
            const result = num1 / num2;
            document.getElementById("result").value = result;
            colorchange('Divide');
            } else {
                openModal("numberWarning"); 
            }
    }
    function power() {
        const num1 = Number(document.getElementById("num1").value);
        const num2 = Number(document.getElementById("num2").value);
        if (num1 != "" && num2 != "") {
            const result = num1 ** num2;
            document.getElementById("result").value = result;
            colorchange('Power');
            } else {
                openModal("numberWarning");
            }
    }
    function root() {
        const num1 = Number(document.getElementById("num1").value);
        const num2 = Number(document.getElementById("num2").value);
        if (num1 != "" && num2 != "") {
            const result = num1 ** (1/num2);
            document.getElementById("result").value = result;
            colorchange('Root');
            } else {
                openModal("numberWarning");
            }
    }
    

    
