﻿# goit-markup-hw-06
 
 
 ```
<div class="">
    <label class="" for="user-email-id">Введіть пошту</label>
    <input class="" type="email" name="user-email" id="user-email-id" placeholder="" autofocus />
</div>
```
```
<div class="">
    <label class="" for="user-tel-id">Введіть телефон</label>
    <input
      type="tel"
      class=""
      name="user-tel"
      id="user-tel-id"
      
      placeholder="Введіть телефон"
      value="+380"- значення

      title="+380 (96) 111-11-11" --(підказка)---
      required ---(поле обовязкове до заповення)---
      autofocus -(автоматично обираеться при завантаженні)--
    />
  </div>
```
```
<button type="submit">Відправити</button>
```
```
<div class="">
    <label class="" for="user-text-id">Ваш коментар</label>
    <textarea
      class=""
      name="user-text"
      id="user-text-id"
      placeholder="Напишіть ваш коментар"
    ></textarea>
(css ----- resize: both | horizontal | vertical | none)
  </div>
```
```
  <fieldset>
    <legend>рамка з написом для групування контенту формы</legend>
  </fieldset>
```

### RADIO
```
<input type="radio" name="size" id="big-id" value="big" checked---(обране поле)--- />
<label for="big-id">big</label>
<input type="radio" name="size" id="small-id" value="small" />
<label for="small-id">small</label>
```

### CHECKBOX
```
<input type="checkbox" name="add" id="tomatos-id" value="tomatos" --checked (обране поле)--- />
<label for="tomatos-id">tomatos</label>
<input type="checkbox" name="add" id="cheese-id" value="cheese" />
<label for="cheese-id">cheese</label>
<input type="checkbox" name="add" id="peperoni-id" value="peperoni" />
<label for="peperoni-id">peperoni</label>
```


### SELECT
```
<select name="city" id="city-id" class="">
    <option value="London" selected(обране за замовчуванням) >London</option>
    <option value="Paris" >Paris</option>
    <option value="Kyiv">Kyiv</option>
</select>
```


### SELECT з підкласами
```
<label for="month">Month</label>
<select name="month" id="month">
  <optgroup label="Summer">
    <option value="s6">June</option>
    <option value="s7">July</option>
    <option value="s8">August</option>
  </optgroup>
   <optgroup label="Autumn">
    <option value="s9">September</option>
    <option value="s10">October</option>
    <option value="s11">November</option>
  </optgroup>
</select>
```

 ##### валідацідація через хак с плейсхолдером якщо плейсхолдера немає долаємо пробіл в placeholder = " "
```
.modal-input:not(:focus):not(:placeholder-shown):valid {
  background-color: rgba(27, 131, 19, 0.361);
}
.modal-input:not(:focus):not(:placeholder-shown):invalid {
  background-color: rgba(131, 62, 19, 0.361);
}
```

##### підсвічуємо обовязкові для заповнення поля з атребутом required 
```
.modal-input:required { 
  border-color: violet;
}

````
```
input:checked + label {
  background-color: #ff6c00;
}
```

#### до placeholder - можна використовувати стилі  як для тексту 
````
.modal-input::placeholder {
  font-size: 12px;
  font-weight: 400;
  color: teal;
}
 ````
 ```
appearance: none - скриває чекбокс
```


