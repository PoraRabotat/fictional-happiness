# fictional-happiness
* {
    box-sizing: border-box;
}
  
.wrapper {
    border: 2px solid #f76707;
    border-radius: 5px;
    gap: 3px;
    background-color: #fff4e6;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
}
  
.box {
    border: 2px solid #ffa94d;
    border-radius: 5px;
    background-color: #ffd8a8;
    padding: 1em;
    color: #d9480f;
}
  
.box1 {
    grid-column: 1 / 4;
}
  
.nested {
    border: 2px solid #ffec99;
    border-radius: 5px;
    background-color: #fff9db;
    padding: 1em;
}
