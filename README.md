// ==UserScript==
// @name         Change Tab Name
// @namespace    http://tampermonkey.net/
// @version      0.1
// @description  none
// @author       İbrahim
// @match        http://*/*
// @icon         data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==
// @grant        none
// ==/UserScript==
document.title = "write tab name here"
var autoRespawn = false
let hue = 10
var settingsRainbow = document.querySelector("#hud-menu-settings")
function changeHue(){
    if(window.rainbowwww){
    hue+=10
    }
}
