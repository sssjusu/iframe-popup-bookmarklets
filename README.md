# iframe-popup-bookmarklets
iframe popup bookmarklets
How to create a bookmarklet: Step One: Open a new tab and press ctrl+shift+o. Step Two: Find a destonation on where to put the hack. Step Three: Right click and select "Add new bookmark". Step Four: Give it a name. Step Five: Copy code from the file "Bookmarklet" in this github page. Step Six: Paste into the url (make sure that at the begining of the url it says "javascript:". Step Seven: Click save. Done! Now just click on the bookmark.

Code for button:
//creates variable called btn
var btn = document.createElement('button');
btn.style.position="fixed";
//puts it where you want it to be at
btn.style.top="5%";
btn.style.right="58%";
btn.zIndex="100000";
//what the button says on it
btn.innerHTML="Close";
document.body.appendChild(btn);
//closes the iframe by changing the size to 0 and makes the button small. make sure there is a varible called frame.
btn.onclick = function() { frame.style.height="0px"; frame.style.width="0px"; btn.style.top="1000%"; btn.style.right="1000%"; };
