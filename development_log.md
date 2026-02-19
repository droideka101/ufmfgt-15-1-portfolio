  
# Week One:  
  
## Task one:  
  
<img width="487" height="219" alt="image" src="https://github.com/user-attachments/assets/b86f92bc-f72a-41a5-9fe9-d1bbaef58aa2" />  
  
## Task two:  
  
<img width="372" height="610" alt="image" src="https://github.com/user-attachments/assets/3e2be120-059c-4202-bfce-03c5f59d7919" />   
  
## Task three:  
  
<img width="722" height="325" alt="Screenshot 2026-01-29 152448" src="https://github.com/user-attachments/assets/9043c1d6-29c5-44e7-bc7a-69bbfdcb162d" />  
  
## Task four:  
  
Psuedo Code  
  
<img width="577" height="292" alt="image" src="https://github.com/user-attachments/assets/b62faa5a-f494-4c49-b86a-57209c8cfb3d" />  
  
### Flow chart  
  
<img width="649" height="446" alt="Screenshot 2026-01-29 151503" src="https://github.com/user-attachments/assets/8e3357ad-381e-41d3-b5f1-e85a8a993238" />  
  
### C code  
  
<img width="583" height="521" alt="Screenshot 2026-01-29 150944" src="https://github.com/user-attachments/assets/3f5b3577-68d0-4c44-bc97-23f200626006" />  
  
## Task six:  

### Test Table  
  
<img width="1040" height="388" alt="image" src="https://github.com/user-attachments/assets/8928996e-91b4-4f3b-8e75-506bb2cd44b5" />  
The code does not work due to the condition for outputing positive is (sum % 2 == 0) which is checking whether the sum is divisible by two, therefor making any even number report as positive, the condition should be (sum > 0)  

# Week Two  

## Task One:

### Psuedo code  

<img width="261" height="269" alt="image" src="https://github.com/user-attachments/assets/737ec8da-e804-42e8-b8d5-4ad00e19be14" />  

### C code  

<img width="582" height="688" alt="image" src="https://github.com/user-attachments/assets/8fce2a19-a3f6-44f9-a29a-49818faf9628" />  

## Task Two:  

### Flow chart  

<img width="690" height="581" alt="image" src="https://github.com/user-attachments/assets/4791526c-8c2b-4910-87c4-776383d40b21" />  

### C code  

<img width="683" height="638" alt="image" src="https://github.com/user-attachments/assets/077efe07-766c-4f94-851a-c947f3a822ee" />

## Task Three:  

### Psuedo Code  

<img width="453" height="258" alt="Screenshot 2026-02-05 145502" src="https://github.com/user-attachments/assets/ab608122-0e06-4ac8-8b77-5bde80dcfc62" />  

### C code  

<img width="609" height="554" alt="Screenshot 2026-02-05 145826" src="https://github.com/user-attachments/assets/7a8489d7-d358-4cd3-8fa0-e28274582ed2" />  

## Task Four:  

### Flow Chart  

<img width="734" height="649" alt="Screenshot 2026-02-05 150612" src="https://github.com/user-attachments/assets/965e44ce-824b-4a5f-b0e8-34a7a8a6b814" />  

### C code  

<img width="981" height="718" alt="Screenshot 2026-02-05 151048" src="https://github.com/user-attachments/assets/e2090a43-8f6e-4310-844d-c214348e6632" />  

## Task Five:  

### Psuedo code  

<img width="509" height="471" alt="Screenshot 2026-02-05 152932" src="https://github.com/user-attachments/assets/6479d2dc-4fc6-49b7-bcc2-3f8f013f8392" />  

### C code  

<img width="788" height="864" alt="Screenshot 2026-02-05 153813" src="https://github.com/user-attachments/assets/97d4f584-7d9e-406e-a09f-5efe9734dda1" />  

## Task Six:  

### C code  

<img width="769" height="566" alt="image" src="https://github.com/user-attachments/assets/58982fa0-624f-41a1-97b4-7ed6bdfd3c07" />  

## Task Seven:

### C code

<img width="666" height="686" alt="image" src="https://github.com/user-attachments/assets/134a8636-b400-4c9c-ac72-2af26e5200c3" />  

# Week Three  

## Task One

### Psuedo Code

<img width="464" height="521" alt="image" src="https://github.com/user-attachments/assets/08eef4b1-dc22-459b-b3a5-b3dfa5275b81" />  

### C code  

<img width="936" height="616" alt="image" src="https://github.com/user-attachments/assets/9edc5e8f-3067-4b70-824f-be42f8fb0d4f" />

## Task Two  

### Psuedo code  

```
START

    FLOAT num1, num2, num3, num4, numTemp

    OUTPUT "Input the 4 values to be sorted"

    INPUT num1, num2, num3, num4 


    // Ascending Order

    IF num1 > num2
        numTemp = num1
        num1 = num2
        num2 = numTemp
    END IF

    IF num1 > num3
        numTemp = num1
        num1 = num3
        num3 = numTemp
    END IF

    IF num1 > num4
        numTemp = num1
        num1 = num4
        num4 = numTemp
    END IF

    IF num2 > num3
        numTemp = num2
        num2 = num3
        num3 = numTemp
    END IF

    IF num2 > num4
        numTemp = num2
        num2 = num4
        num4 = numTemp
    END IF

    IF num3 > num4
        numTemp = num3
        num3 = num4
        num4 = numTemp
    END IF

    OUTPUT "Ascending order:", num1, num2, num3, num4


    // Descending Order

    IF num1 < num2
        numTemp = num1
        num1 = num2
        num2 = numTemp
    END IF

    IF num1 < num3
        numTemp = num1
        num1 = num3
        num3 = numTemp
    END IF

    IF num1 < num4
        numTemp = num1
        num1 = num4
        num4 = numTemp
    END IF

    IF num2 < num3
        numTemp = num2
        num2 = num3
        num3 = numTemp
    END IF

    IF num2 < num4
        numTemp = num2
        num2 = num4
        num4 = numTemp
    END IF

    IF num3 < num4
        numTemp = num3
        num3 = num4
        num4 = numTemp
    END IF

    OUTPUT "Descending order:", num1, num2, num3, num4

END
```

### C code  

<img width="1074" height="873" alt="image" src="https://github.com/user-attachments/assets/0614f3cf-afa2-4908-8421-e0cb0dac759c" />

## Task Three  

### Psuedo code

# Random Number Guessing Game (Pseudocode)

```
START

    INT randomValue = rand() % 101
    INT userGuess

    OUTPUT "Guess the random number (3/3 guesses remaining)"
    INPUT userGuess

    IF userGuess == randomValue
        OUTPUT "Correct!"
        RETURN
    ELSE
        IF userGuess < randomValue
            OUTPUT "Too low, guess again (2/3 guesses remaining)"
        ELSE
            OUTPUT "Too high, guess again (2/3 guesses remaining)"

    INPUT userGuess

    IF userGuess == randomValue
        OUTPUT "Correct!"
        RETURN
    ELSE
        IF userGuess < randomValue
            OUTPUT "Too low, guess again (1/3 guesses remaining)"
        ELSE
            OUTPUT "Too high, guess again (1/3 guesses remaining)"

    INPUT userGuess

    IF userGuess == randomValue
        OUTPUT "Correct!"
        RETURN
    ELSE
        IF userGuess < randomValue
            OUTPUT "Too low, 0/3 guesses remaining"
        ELSE
            OUTPUT "Too high, 0/3 guesses remaining"

END
```

### C code  

<img width="1408" height="868" alt="image" src="https://github.com/user-attachments/assets/0c7d2ccf-1237-4b3b-99ea-40ee5da157f4" />  

## Task Four  

### Psuedo code

<img width="621" height="421" alt="image" src="https://github.com/user-attachments/assets/d532a76a-ac97-4865-878a-6d7185fc0869" />  

### C code

<img width="1130" height="875" alt="image" src="https://github.com/user-attachments/assets/c4219824-9994-45f7-8328-8b1d5bce4926" />  

## Task Five  

### Psuedo code  

<img width="487" height="432" alt="image" src="https://github.com/user-attachments/assets/cb982549-d9dc-4184-9133-7dd22e4bb5bb" />  

### C code  

<img width="1046" height="818" alt="image" src="https://github.com/user-attachments/assets/46104cb2-848c-43b6-b7fb-d9c9c1abb868" />  

## Task Six  

### Psuedo code  

<img width="729" height="452" alt="image" src="https://github.com/user-attachments/assets/718f3476-8dae-4c9e-9bc3-fb51f2f12586" />  

### C code  

<img width="1142" height="884" alt="image" src="https://github.com/user-attachments/assets/a154a8e6-9a06-467b-b663-9fd828c0729e" />  

## Task Seven

### Psuedo code

<img width="652" height="276" alt="image" src="https://github.com/user-attachments/assets/16b5a45d-fc4b-4894-a667-29d067b0af13" />  

### C code  

<img width="1134" height="746" alt="image" src="https://github.com/user-attachments/assets/c726ae02-49eb-49fd-a0c0-0b09d759d38d" />  

## Task Eight

### Psuedo code

<img width="414" height="228" alt="image" src="https://github.com/user-attachments/assets/03bc979b-7e1a-41f1-869b-0c7adc1a015a" />

### C code

<img width="913" height="605" alt="image" src="https://github.com/user-attachments/assets/d6ddf39c-c261-4e58-a6c7-1bd5068e654b" />  






