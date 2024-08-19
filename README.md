# lottiwe.github.io
<h1> this is my site </h1>
<p> Welcome to website </p>
<a href="https://codepen.io/las-/pen/GRbmPrd">click here for some other amazing work</a> 

/* HTML: <div class="loader"></div> */
.loader {
  width: 70px;
  height: 50px;
  box-sizing: border-box;
  background:
    conic-gradient(from 135deg at top,#0000, #fff 1deg 90deg,#0000 91deg) right -20px bottom 8px/18px 9px,
    linear-gradient(#fff 0 0) bottom/100% 8px,
    #000;
  background-repeat: no-repeat;
  border-bottom: 8px solid #000;
  position: relative;
  animation: l7-0 2s infinite linear;
}
.loader::before {
  content: "";
  position: absolute;
  width: 10px;
  height: 14px;
  background: lightblue;
  left: 10px;
  animation: l7-1 2s infinite cubic-bezier(0,200,1,200);
}
@keyframes l7-0{
  100% { background-position: left -20px bottom 8px,bottom}
}
@keyframes l7-1{
  0%,50%   {bottom: 8px}
  90%,100% {bottom: 8.1px}
}
