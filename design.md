# Button style

### Normal Button

<img src="https://i.ibb.co/RNR6By1/button.png">

```
<button class="btn">Save</button>
```

```
.btn {
  border: none;
  outline: none;
  cursor: pointer;
  padding: 8px 16px;
  border-radius: 5px;
  background-color: lavender;
}
```

<hr>

### Outline Button

<img src="https://i.ibb.co/9hYS2Kq/button-outline.png">

```
 <button class="btn-outline">Save</button>
```

```
.btn-outline {
  border: 1px solid lightblue;
  color: black;
  background-color: transparent;
  outline: none;
  cursor: pointer;
  padding: 8px 16px;
  border-radius: 5px;
}
```

<hr>

### Round Button

<img src="https://i.ibb.co/PTjzLBN/button-round.png">

```
 <button class="btn-round">Save</button>
```

```
.btn-round {
  border: none;
  outline: none;
  cursor: pointer;
  padding: 8px 16px;
  border-radius: 26px;
  background-color: lightskyblue;
}
```

<hr>

# Input style

### Normal input

<img src="https://i.ibb.co/zmZXPb6/input.png">

```
<input type="text" class="input-text" placeholder="Username" />
```

```
.input-text {
  display: block;
  padding: 8px;
  border: none;
  background-color: #f1f1f1;
  border-radius: 5px;
  outline: none;
  font-family: inherit;
}
```

<hr>

### Outline Input

<img src="https://i.ibb.co/5BrL54n/input2.png">

```
<input type="text" class="input-text-outline" placeholder="Username" />
```

```
.input-text-outline {
  display: block;
  padding: 8px;
  border: 1px solid lightgrey;
  border-radius: 5px;
  outline: none;
}
```

<hr>

### Textarea

<img src="https://i.ibb.co/SJHspcT/textarea.png">

```
<textarea cols="30" rows="5" placeholder="description"></textarea>
```

```
textarea {
  padding: 10px;
  outline: none;
}
```

<hr>

# Radio button

<img src="https://i.ibb.co/3Yfq0vp/radio.png">

```
<input type="radio" name="gender" id="male" />
<label for="male">Male</label>
<br />
<input type="radio" name="gender" id="female" />
<label for="female">Female</label>
```

<hr>

# checkbox

<img src="https://i.ibb.co/1bfzhGg/checkbox.png">

```
<input type="checkbox" id="html" />
<label for="html">html</label>
<br />
<input type="checkbox" id="css" />
<label for="css">css</label>
<br />
<input type="checkbox" id="javascript" />
<label for="javascript">javascript</label>
```

<hr>

# Select

<img src="https://i.ibb.co/MZ85yNz/select.png">

```
<select name="size" id="size">
<option value="s">Small</option>
<option value="m">Meduim</option>
<option value="l">Large</option>
</select>
```

```
select {
  padding: 8px;
  outline: none;
  border: 1px solid lightgrey;
  border-radius: 5px;
}
```

<hr>

# Card container

<img src="https://i.ibb.co/ZY8N1tg/cards.png">

```
  <div class="card-container">
      <div class="card">
        <div class="card-header">
          <h1>Card title</h1>
        </div>
        <div class="card-body">
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam,
            quidem.
          </p>
        </div>
      </div>
      <div class="card">
        <div class="card-header">
          <h1>Card title</h1>
        </div>
        <div class="card-body">
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam,
            quidem.
          </p>
        </div>
      </div>
      <div class="card">
        <div class="card-header">
          <h1>Card title</h1>
        </div>
        <div class="card-body">
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam,
            quidem.
          </p>
        </div>
      </div>
  </div>
```

```
.card-container {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  width: 100%;
  gap: 20px;
}

.card {
  width: 300px;
  background-color: #f1f1f1;
  border-radius: 12px;
  padding: 10px;
}
```

<hr>

# Two col item

<img src="https://i.ibb.co/m5CynqD/two-col.png">

```
<div class="two-col">
  <i class="fab fa-facebook"></i>
  <i class="fab fa-instagram"></i>
</div>
```

```
.two-col {
  display: flex;
  justify-content: space-between;
}
```

<hr>

# three col item

<img src="https://i.ibb.co/r75RDbH/three-col.png">

```
<div class="three-col">
  <i class="fab fa-facebook"></i>
  <i class="fab fa-instagram"></i>
  <i class="fab fa-twitter"></i>
</div>
```

```
.three-col {
  display: flex;
  justify-content: space-between;
}
```

<hr>

# Header

<img src="https://i.ibb.co/HFn9LBQ/header.png">

```
<div class="header">
  <div class="header-container">
    <div class="left-header">
      <h1>Explore the Space</h1>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Beatae
        recusandae iusto numquam dolorum provident facilis asperiores
        consequatur fugiat eos odio.
      </p>
      <button class="btn">Book now</button>
    </div>
    <div class="right-header">
      <img src="header.svg" alt="" />
    </div>
  </div>
</div>
```

```
.header {
  background-color: lightsteelblue;
}
.header-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 100vh;
  width: 100%;
  max-width: 1200px;
  margin: auto;
  gap: 20px;
}
.left-header p {
  margin-top: 10px;
  margin-bottom: 25px;
}
```

<hr>

# Navbar

<img src="https://i.ibb.co/tzQp2kb/navbar.png">

```
<nav>
  <div class="nav-container">
    <div class="left-nav">
      <a href="">Home</a>
      <a href="">About</a>
      <a href="">Contact</a>
    </div>
    <div class="right-nav">
      <button class="btn">login</button>
    </div>
  </div>
</nav>
```

```
nav {
  background-color: lightgoldenrodyellow;
  padding: 20px;
}
.nav-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.left-nav a {
  color: inherit;
  margin-right: 10px;
  font-size: 18px;
}
```

<hr>
