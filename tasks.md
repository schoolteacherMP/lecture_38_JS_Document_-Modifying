## Задача 1.   
### createTextNode vs innerHTML vs textContent  
У нас есть пустой DOM-элемент elem и строка text.  
Какие из этих 3-х команд работают одинаково?  
**elem.append(document.createTextNode(text))  
elem.innerHTML = text  
elem.textContent = text  **

## Задача 2.   
### Очистите элемент  
Создайте функцию clear(elem), которая удаляет всё содержимое из elem.  
![image](https://user-images.githubusercontent.com/113675674/216989307-d869f5e4-7f00-4f8e-aa7c-cfc32214e37f.png)  

## Задача 3.   
### Почему остаётся "aaa"?  
В примере ниже вызов table.remove() удаляет таблицу из документа.  
Но если вы запустите его, вы увидите, что текст "aaa" все еще виден.  
Почему так происходит?  
`<table id="table">`
  `aaa`
  `<tr>`
   `<td>Тест</td>`
  `</tr>`
`</table>`

`<script>`
  `alert(table); // таблица, как и должно быть`

  `table.remove();`
  `// почему в документе остался текст "ааа"?`
`</script>`

## Задача 4.   
### 

## Задача 5.   
### 

## Задача 6.   
### 

## Задача 7.   
### 

## Задача 8.   
### 

## Задача 9.   
### 

## Задача 10.   
### 
