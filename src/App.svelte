<script>

let arrayNumbers = [0,1,2,3,4,5,6,7,8,9]
let arrayOperators = ['+','-','/','*']
let rightNum = '';
let letNum = '';
let operator = '';
// let arrayOperators = ´[]

    function saveNumber (numbers){
        if(operator ==! ''){
            letNum += numbers;
        }else{
            rightNum += numbers;
        }
        console.log (numbers);
    }

    function saveOperator (number){
        operator =
        console.log (number);
    }


</script>

<h1>I'm ready!</h1>

{#each arrayNumbers as number}
<button on:click={function(){saveNumber(number)}}>{number}</button>
{/each}

{#each arrayOperators as operator}
<button on:click={function(){saveOperator(operator)}}>{operator}</button>
{/each}

<p>{letNum}</p>
<p>{rightNum}</p>
<p>{rightNum}</p>

<!-- <button>2</button>
<button>3</button>
<button>4</button>
<button>5</button>
<button>+</button> -->
