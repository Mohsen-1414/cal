Hello!

   <label>Number 2</label>
    <input placeholder="Number 2" id="num2">


    if(button.value === 'Add'){
        var sum = parseInt(digit1) + parseInt(digit2);
        label.textContent = `${digit1} + ${digit2}  =  ${sum}`;
    }
    else{
        var sum = parseInt(digit1) - parseInt(digit2);
        label.textContent = `${digit1} - ${digit2}  =  ${sum}`;