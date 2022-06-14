@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@500&display=swap");

html {
  font-size: 18px;
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: black;
  font-family: "roboto";


}

header {
  background-color: #6495ed;
  padding: 20px;
  width: 100%;
  position: fixed;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  z-index: 1;

}
.nav-list {
  font-size: 16;
  display: flex;
  color: red;
  justify-content: space-between;
  align-items: center;
  list-style: none;
  margin: 0;
  padding: 0;

}
.topBar nav {
  width: 100%;
  margin: 0 auto;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;


}
.topBar nav ul li {
  color: #fff;
  display: flex;
  padding: 10px 20px;
  border-bottom: 2px solid #1e90ff;
  font-size: 22px;
  font-weight: bold;
  text-transform: uppercase;
  font-family: "roboto";
  list-style: none;
  margin: 0;
  
  
}
.topBar nav ul li:hover {
  cursor: pointer;
  border-bottom: 2px solid #fff;
}

.logo {
  color: white;
  font-size: 36px;
  flex-direction: row;
  top: 100px;
}
.container-cards {
  position: relative;
  top: 90px;
  background-color: #f0f0f0; 
  box-shadow: 0px 0px 10px #000;
  z-index: 1;
}
.banner {
  width: 100%;
  height: 400px;
  background-image: url(../img/sptw-2019.jpg);
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  box-shadow: 0px 0px 10px #000;
  z-index: 1;
}
.container-card {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  justify-content: center;
  align-items: center;
  background-color: grey;

}
.card {   width: 350px;
  height: 300px;
  border: 1px solid #87cefa;
  border-radius: 10px;
  display: flex;
  flex-direction: column;
  align-items: center;
  background-color: #87cefa;

}

.card__desc {
  flex-grow: 1;
  overflow-y: hidden;
}
.cards-title {  
  font-size: 24px;
  font-weight: bold;
  text-transform: uppercase;
  color: #fff;
  text-align: center;
  margin-bottom: 20px;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  background-color: #87cefa;
  padding: 10px;
  border-radius: 10px;
}
footer{
  background-color: #6495ed;
  padding: 20px;
  width: 100%;
  position: fixed;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  z-index: 1;

}