<!-- StyleSheet --->
<!--- Using CSS Style Sheet was Created  --->
body {
    background-color: whitesmoke;
}
.outerDiv {
    width: 58vw;
    margin: 60px auto 60px auto;
    background-color: darkslategray;
    color: darkslategray;
    border-radius: 6px;
}
.Heading{
    color: orange;
}
h1 {
    margin: auto;
    padding-top: 30px;
    padding-bottom: 10px;
    padding-left: 30px;
}
.flexcontainer {
    display: flex;
    justify-content: flex-start;
    background-color: rgb(227, 227, 252);
}
.outerContainer {
    padding-left: 30px;
    padding-right: 30px;
    color: darkslategray;
    display: flex;
    flex-direction: column;
    align-items: flex-end;
}
.innerContainer{
    padding-top: 40px;
}
label {
    margin-right: 20px;
}
.select {
    margin-right: 20px;
}
form input {
    width: 200px;
    border: 1px solid grey;
    border-radius: 6px;
    padding: 6px 18px;
    background-color: whitesmoke;
    cursor: pointer;
    font-family: 'Times New Roman', Times, serif;
    margin-top: 6px;
    font-size: 16px;
}
.button {
    margin-top: 16px;
}
form select {
    width: 240px;
    border: 1px solid grey;
    border-radius: 6px;
    padding: 6px 16px;
    text-align: center;
    background-color: whitesmoke;
    cursor: pointer;
    margin-top: 6px;
    font-family: 'Times New Roman', Times, serif;
    font-size: 16px;
}
button {
    font-weight: bold;
    font-family: sans-serif;
    border: none;
    border-radius: 25px;
    padding: 8px 18px;
    background-color: black;
    color: white;
    cursor: pointer;
    font-family: 'Times New Roman', Times, serif;
}

.mybutton {
    padding-top: 30px;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: rgb(227, 227, 252);
}
.buttonDiv {
    background-color: rgb(227, 227, 252);
    margin: 20px auto;
}
.buttonStyle {
    background-color: black;
    color: white;
    border: none;
    padding: 8px 18px;
    font-family: 'Times New Roman', Times, serif;
}
.myFuter {
    background-color: rgb(227, 227, 252);
    border-top: 1pt solid darkslategray;
    padding-top: 10px;
    padding-bottom: 30px;
}
p {
    color: grey;
    text-align: center;
    margin: auto;
}
p a {
    color: darkgreen;
    text-decoration: none;
    margin: auto;
}


/*  Screen No- 1  */
@media screen and (min-width: 320px) and (max-width: 340px) {
    .outerDiv {
        width: 95vw;
        margin: 10px auto 40px auto;
    }
    .outerContainer {
        padding-left: 20px;
        padding-right: 20px;
    }
    .innerComtainer {
        padding-top: 60px;
    }
}
