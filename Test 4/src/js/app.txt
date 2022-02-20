// NOTE: This pen was created for explaining the idea of Multi language content with css. Please ignore any unresponsive elements. 

var htmlElement = document.querySelector("html");

document.querySelector("label").onclick = function() {
  if(htmlElement.getAttribute("lang") == "en") {
    document.querySelector("html").setAttribute("lang", "ru");
  } else if(htmlElement.getAttribute("lang") == "ru") {
    document.querySelector("html").setAttribute("lang", "en");
  }
}