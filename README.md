
noStroke();

// position of the car
var x = 11;

var i = 10;
var draw = function() {
    background(252, 255, 214);
    
    // draw the wheels
    fill(50, 62, 227);
    ellipse(x + 50, 221, i, i);
    ellipse(x + 300, 221, 2*i, 2*i);
    
    if (i%40 === 0){
        i-=31;
    }
    else if (i % 66 ===0){
        i+= 31;
    }
    
    
    i++;
};
