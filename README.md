# goit-markup-hw-06

<div class="">
    <label class="" for="user-email-id">������ �����</label>
    <input class="" type="email" name="user-email" id="user-email-id" placeholder="" autofocus />
</div>
  
<div class="">
    <label class="" for="user-tel-id">������ �������</label>
    <input
      type="tel"
      class=""
      name="user-tel"
      id="user-tel-id"
      
      placeholder="������ �������"
      value="+380"- ��������

      title="+380 (96) 111-11-11" --(�������)---
      required ---(���� ���������� �� ���������)---
      autofocus -(����������� ���������� ��� �����������)--

    />
  </div>

<button type="submit">³��������</button>

<div class="">
    <label class="" for="user-text-id">��� ��������</label>
    <textarea
      class=""
      name="user-text"
      id="user-text-id"
      placeholder="�������� ��� ��������"
    ></textarea>
(css ----- resize: both | horizontal | vertical | none)
  </div>


  <fieldset>
    <legend>����� � ������� ��� ���������� �������� �����</legend>
  </fieldset>

RADIO
<input type="radio" name="size" id="big-id" value="big" checked---(������ ����)--- />
<label for="big-id">big</label>
<input type="radio" name="size" id="small-id" value="small" />
<label for="small-id">small</label>


CHECKBOX
<input type="checkbox" name="add" id="tomatos-id" value="tomatos" --checked (������ ����)--- />
<label for="tomatos-id">tomatos</label>
<input type="checkbox" name="add" id="cheese-id" value="cheese" />
<label for="cheese-id">cheese</label>
<input type="checkbox" name="add" id="peperoni-id" value="peperoni" />
<label for="peperoni-id">peperoni</label>


<select name="city" id="city-id" class="">
    <option value="London" selected(������ �� �������������) >London</option>
    <option value="Paris" >Paris</option>
    <option value="Kyiv">Kyiv</option>
</select>

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


������������ ������������ ���� ������������ ���� ������ ����� � placeholder = " "

.modal-input:not(:focus):not(:placeholder-shown):valid {
  background-color: rgba(27, 131, 19, 0.361);
}
.modal-input:not(:focus):not(:placeholder-shown):invalid {
  background-color: rgba(131, 62, 19, 0.361);
}


�������� ��������� ��� ���������� ���� � ��������� required 

.modal-input:required { 
  border-color: violet;
}

input:checked + label {
  background-color: #ff6c00;
}


(�� placeholder - ����� ��������������� ����  ��� ������ �������������)
.modal-input::placeholder {
  font-size: 12px;
  font-weight: 400;
  color: teal;
}
 
.modal-text input::placeholder { 
color: tomato;
}

appearance: none - ������ �������
