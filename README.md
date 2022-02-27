# video-conference-website
*{
margins:0;
padding:0;
box-sizing:border box;
font-family:'Poppins,'sans-serif';
}

.header {
       width:100%;
       height:100vh;
       background:dark;
       position:relative;
       }
  nav{
  position:absolute;
  top:0;
  left:0;
  bottom:0;
  background:#182842;
  width:120px;
  padding: 10px 0;
  }
  nav.logo {
  width:56px;
  display:block;
  margin:auto;
  cursor:pointer;
  }
  nav ul {
  margin-top: 160px;
  }
  
  nav ul li {
  list-style:none;}
  
  nav ul li img {
  width:50px;
  display:block;
  margin: 10px auto;
  padding:10px;
  cursor:pointer;
  opacity:0.5;
  border radius:10px;
  transition: opacity 0.5s
  background 0.5s
  }
  nav ul li img : hover {
  opacity:1
  background:#4d6182;
  }
  .active {
  opacity:1;
  background:#4d6181;
  }
  .container {
  marrgin-left :120px;
  padding : 0 2.5%;
  }
  .top-icons {
  display: flex;
  align-items:center;
  justify-content:flex-end;
  padding:25% 0;
  }
  .top-icon img {
  width : 25px;
  margin-left:40px;
  cursor:pointer;
  }
  .row {
  margin-top: 15px;
  display: flex;
  justify-content:space-between;
  }
  .col-1 {
  flex-basis:33%;
  }
  .host-img {
  width:100%;
  border radius:15px;
  }
  .controls {
  display:flex;
  align-items:center;
  justify-content: center;
  }
  .controls img {
  width:40px;
  margin :20px 10px;
  cursor: pointer;
  transition:transform 0.5s
  }
  .joined {
  background: #182842;
  border-radius:15px;
  padding: 30px 40px 50px;
  color: #fff;
  }
  .joined div {
  margin-top:20px;
  display: grid;
  grid template .column : auto auto auto;
  grid-gap: 20px;
  }
  .joined img {
  width: 100%;
  border-radius:10px;
  cursor:pointer;
  }
  .invite {
  background: #182842;
  border-radius:15px;
  padding: 30px 40px 50px;
  color: #fff;
  margin-top:20px;
  }
  .invite img {
  margin-top: 20px;
  width:50px;
  marging-left:5px;
  border-radius:50%;
  cursor: pointer;
  }
