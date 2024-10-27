# shapessketch

function setup() {
  createCanvas(400, 400);
  background(220);
  noLoop(); // Prevents continuous looping
}

function draw() {
  // Draw the house body
  fill(200, 100, 100);
  beginShape();
  vertex(100, 200);
  vertex(300, 200);
  vertex(300, 350);
  vertex(100, 350);
  endShape(CLOSE);

  // Draw the roof
  fill(150, 75, 0);
  beginShape();
  vertex(80, 200);
  vertex(200, 120);
  vertex(320, 200);
  endShape(CLOSE);

  // Draw the door
  fill(100, 50, 50);
  beginShape();
  vertex(180, 280);
  vertex(220, 280);
  vertex(220, 350);
  vertex(180, 350);
  endShape(CLOSE);

  // Draw left window
  fill(100, 150, 200);
  beginShape();
  vertex(120, 220);
  vertex(160, 220);
  vertex(160, 260);
  vertex(120, 260);
  endShape(CLOSE);

  // Draw right window
  fill(100, 150, 200);
  beginShape();
  vertex(240, 220);
  vertex(280, 220);
  vertex(280, 260);
  vertex(240, 260);
  endShape(CLOSE);
}
