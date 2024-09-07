let buttons = document.querySelectorAll(".data");
let display = document.querySelector(".display");
let string = " ";

buttons.forEach((button) => {
    button.addEventListener("click", () => {
        let value = button.value;

        if(value==="="){
        string = eval(string);
        display.innerText = string;
    }

    else if(value === "CLR"){
        string = ""
        display.innerText="0";
    
    }
    else if(value==="AC"){
        
      
            string = string.slice(0, -1); // Remove the last character
            display.innerText = string; // Update the display
        }
        
    
    else{
        string = string + value;
        display.innerText = string;
        }

     
     
    });
});
