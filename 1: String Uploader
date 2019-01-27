var textfield;
var output;
var submit;

function setup() {
    noCanvas();
    //textfield = createInput("your favourite food");
    textfield = select("#textfield")
    //textfield.changed(newText);
    textfield.input(newTyping);
    output = select('#output');
    submit = select("#submit")
    submit.mousePressed(newText);
}

function draw() {
}

function newText() {
  createP(textfield.value());
}

function newTyping() {
  //createP(textfield.value());
  output.html(textfield.value());
}
