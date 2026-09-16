document.getElementById("year").textContent = new Date().getFullYear();
if ("serviceWorker" in navigator) window.addEventListener("load",()=>navigator.serviceWorker.register("/sw.js"));
document.querySelectorAll("nav a").forEach(a=>a.addEventListener("click",()=>document.body.classList.remove("nav-open")));