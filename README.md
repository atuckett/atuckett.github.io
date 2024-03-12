@import url("https://fonts.googleapis.com/css2?family=Roboto&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "Roboto", sans-serif;
  min-height: 100vh;
  padding: 20px;
}

.container {
  max-width: 800px;
  min-height: 400px;
  margin-inline: auto;
  border: 1px solid #000;
  display: flex;
  gap: 1rem;
  justify-content: center;
  align-items: center;
  flex-flow: row wrap;
  align-content: space-evenly;
} 

.box {
  /* min-width: 100px; */
  height: 100px;
  background-color: #000;
  color: #fff;
  font-size: 2rem;
  padding: 0.5rem;

  display: flex;
  justify-content: center; 
  align-items: center;

  flex: 1 1 150px;
}

.box:nth-child(2) {
  flex: 2 2 150px;
  order: 1;
}


