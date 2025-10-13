bài 2

body {
  margin: 0;
  padding: 0;
  background-color: white;
  font-family: sans-serif;
}

.container {
  display: flex;
  justify-content: center;
  align-items: flex-end;
  height: 100vh;
  gap: 10px; /* khoảng cách giữa các khối */
}

.box {
  width: 80px;
  background-color: #666;
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 16px;
}





   bài 4

   * {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background-color: lightgray;
  font-family: sans-serif;
}

/* Header */
.header {
  display: flex;
}

.menu {
  flex: 1;
  text-align: center;
  padding: 10px;
  background-color: gray;
  color: white;
  border: 1px solid #999;
}

/* Main content */
.main {
  display: flex;
  height: 60vh;
}

.item {
  border: 1px solid gray;
  background-color: #eee;
  padding: 10px;
  font-weight: bold;
}

.item1 {
  width: 20vw;
}

.item2 {
  width: 20vw;
}

.item3 {
  width: 60vw;
}

/* Footer */
.footer {
  display: flex;
  height: 40vh;
}

.footer div {
  width: 50vw;
  border: 1px solid gray;
  background-color: #eee;
  padding: 10px;
  font-weight: bold;
}

