#Basic-Calculator-in-Html

Here is calculator coded in HTML 

///////// code below//////////

<html>
<head>
    <title>Calculator - HIMANSHU AHUJA</title>
    <style>
        
    #calc-contain{
        position: relative;
        width: 600px;
        border: 2px solid black;
        border-radius: 12px;
        margin: 0px auto;
        padding: 20px 20px 100px 20px;
        }
    #agh{
        position: relative;
        float: right;
        margin-top: 15px;
    }
    #agh p{
        font-size: 20px;
        font-weight: 900;
    }
    input[type=button] {
        background: lightGray;
        width: 15%;
        font-size: 20px;
        font-weight: 900;
        border-radius: 7px;
        margin-left: 13px;
        margin-top: 10px;
    }
    input[type=button]:active {
        background-color: #3e8e41;
        box-shadow: 0 5px #666;
        transform: translateY(4px);
    }
    input[type=button]:hover {
        background-color: #003300;
        color: white;
    }
    
    input[type = text] {
        position: relative;
        display: block;
        width: 90%;
        margin: 5px auto;
        font-size: 20px;
        padding: 10px;
        box-shadow: 4px 0px 12px black inset;
    }
    
    #agh p4{
        font-size: 28px;
        font-weight: 900;
        margin-left: 50px;
        border: 2px solid black;
    }
    </style>
    <script type="text/javascript">
    var calculator_on=false;
    var calculator_start=false;
    
    function on_function(){
        document.getElementById('answer').readonly='false';
        document.getElementById('answer').value="0.0";
        calculator_on=false;
        calculator_start=true;
    }
    
    function off_function(){
        
        document.getElementById('answer').value="";
        document.getElementById('answer').readonly='true';
        calculator_on=false;
        calculator_start=false;
    }
    
    function button_0(){
        var temp;
        temp=document.getElementById('answer').value;
        if (calculator_start == false){
            
        } else {
            if (calculator_on == false){
                document.getElementById('answer').value= '0';
                calculator_on = true;
            } else {
                document.getElementById('answer').value += '0';
            }

        }
    }
    
    function button_1(){
        var temp;
        temp=document.getElementById('answer').value;
        if (calculator_start == false){
            
        } else {
            if (calculator_on == false){
                document.getElementById('answer').value= '1';
                calculator_on = true;
            } else {
                document.getElementById('answer').value += '1';
            }
            
        }
    }
    
    function button_2(){
        var temp;
        temp=document.getElementById('answer').value;
        if (calculator_start == false){
            
        } else {
            if (calculator_on == false){
                document.getElementById('answer').value= '2';
                calculator_on = true;
            } else {
                document.getElementById('answer').value += '2';
            }
            
        }
    }
    
    function button_3(){
        var temp;
        temp=document.getElementById('answer').value;
        if (calculator_start == false){
            
        } else {
            if (calculator_on == false){
                document.getElementById('answer').value= '3';
                calculator_on = true;
            } else {
                document.getElementById('answer').value += '3';
            }
            
        }
    }
    
    function button_4(){
        var temp;
        temp=document.getElementById('answer').value;
        if (calculator_start == false){
            
        } else {
            if (calculator_on == false){
                document.getElementById('answer').value= '4';
                calculator_on = true;
            } else {
                document.getElementById('answer').value += '4';
            }
            
        }
    }
    
    function button_5(){
        var temp;
        temp=document.getElementById('answer').value;
        if (calculator_start == false){
            
        } else {
            if (calculator_on == false){
                document.getElementById('answer').value= '5';
                calculator_on = true;
            } else {
                document.getElementById('answer').value += '5';
            }
            
        }
    }
    
    function button_6(){
        var temp;
        temp=document.getElementById('answer').value;
        if (calculator_start == false){
            
        } else {
            if (calculator_on == false){
                document.getElementById('answer').value= '6';
                calculator_on = true;
            } else {
                document.getElementById('answer').value += '6';
            }
            
        }
    }
    
    function button_7(){
        var temp;
        temp=document.getElementById('answer').value;
        if (calculator_start == false){
            
        } else {
            if (calculator_on == false){
                document.getElementById('answer').value= '7';
                calculator_on = true;
            } else {
                document.getElementById('answer').value += '7';
            }
            
        }
    }
    
    function button_8(){
        var temp;
        temp=document.getElementById('answer').value;
        if (calculator_start == false){
            
        } else {
            if (calculator_on == false){
                document.getElementById('answer').value= '8';
                calculator_on = true;
            } else {
                document.getElementById('answer').value += '8';
            }
            
        }
    }
    
    function button_9(){
        var temp;
        temp=document.getElementById('answer').value;
        if (calculator_start == false){
            
        } else {
            if (calculator_on == false){
                document.getElementById('answer').value= '9';
                calculator_on = true;
            } else {
                document.getElementById('answer').value += '9';
            }
            
        }
    }
    
    function button_01(){
        var temp;
        temp=document.getElementById('answer').value;
        if (calculator_start == false){
            
        } else {
            if (calculator_on == false){
                document.getElementById('answer').value= '.';
                calculator_on = true;
            } else {
                document.getElementById('answer').value += '.';
            }
            
        }
    }
    
    function button_02(){
        var temp;
        temp=document.getElementById('answer').value;
        if (calculator_start == false){
            
        } else {
            if (calculator_on == false){
                document.getElementById('answer').value= '(';
                calculator_on = true;
            } else {
                document.getElementById('answer').value += '(';
            }
            
        }
    }
    
    function button_03(){
        var temp;
        temp=document.getElementById('answer').value;
        if (calculator_start == false){
            
        } else {
            if (calculator_on == false){
                document.getElementById('answer').value= ')';
                calculator_on = true;
            } else {
                document.getElementById('answer').value += ')';
            }
            
        }
    }
    
    function button_04(){
        var temp;
        temp=document.getElementById('answer').value;
        if (calculator_start == false){
            
        } else {
            if (calculator_on == false){
                document.getElementById('answer').value= '+';
                calculator_on = true;
            } else {
                document.getElementById('answer').value += '+';
            }
            
        }
    }
    
    function button_05(){
        var temp;
        temp=document.getElementById('answer').value;
        if (calculator_start == false){
            
        } else {
            if (calculator_on == false){
                document.getElementById('answer').value= '-';
                calculator_on = true;
            } else {
                document.getElementById('answer').value += '-';
            }
            
        }
    }
    
    function button_06(){
        var temp;
        temp=document.getElementById('answer').value;
        if (calculator_start == false){
            
        } else {
            if (calculator_on == false){
                document.getElementById('answer').value= '*';
                calculator_on = true;
            } else {
                document.getElementById('answer').value += '*';
            }
            
        }
    }
    
    function button_07(){
        var temp;
        temp=document.getElementById('answer').value;
        if (calculator_start == false){
            
        } else {
            if (calculator_on == false){
                document.getElementById('answer').value= '/';
                calculator_on = true;
            } else {
                document.getElementById('answer').value += '/';
            }
            
        }
    }
    
    function button_08(){
        var temp;
        temp=document.getElementById('answer').value;
        if (calculator_start == false){
            
        } else {
            if (calculator_on == false){
                
            } else {
                document.getElementById('answer').value = eval(document.getElementById('answer').value);
                
            }
            
        }
    }
    
    function button_09(){
        var temp;
        temp=document.getElementById('answer').value;
        if (calculator_start == false){
            
        } else {
            
                document.getElementById('answer').value= '0.0';
                calculator_on = false;
        }
    }
   
    
    </script>
</head>
<body>
    <div id='calc-contain'>
        
        <form name="calculator">
            <h1 align="center">My calculator</h1>
            
            <input type="text" name="answer" id="answer" />
            <br>
            

            <input type="button" value=" on " id="on" onclick="on_function()" />
            <input type="button" value=" off " id="off" onclick="off_function()" />
            <input type="button" value=" 0 " onclick="button_0()" />
            <input type="button" value=" 1 " onclick="button_1()" />
            <br/>
            
            <input type="button" value=" 2 " onclick="button_2()" />
            <input type="button" value=" 3 " onclick="button_3()" />
            <input type="button" value=" 4 " onclick="button_4()" />
            <input type="button" value=" 5 " onclick="button_5()" />
            </br>
            
            <input type="button" value=" 6 " onclick="button_6()" />
            <input type="button" value=" 7 " onclick="button_7()" />
            <input type="button" value=" 8 " onclick="button_8()" />
            <input type="button" value=" 9 " onclick="button_9()" />
            </br>
            
            <input type="button" value=" . " onclick="button_01()" ß/>
            <input type="button" value=" ( " onclick="button_02()" />
            <input type="button" value=" ) " onclick="button_03()" />
            <input type="button" value=" + " onclick="button_04()" />
            <input type="button" value=" - " onclick="button_05()" />
            </br>
            
            
            <input type="button" value=" x " onclick="button_06()" />
            <input type="button" value=" / " onclick="button_07()" />
            <input type="button" value=" = " onclick="button_08()" />
            <input type="button" value=" clear " onclick="button_09()" />
            </br>
            
            
        </form>
    </div>
</body>
</html>
