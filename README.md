# DeleteLinkedinPosts
Delete your Linkedin Posts

Recently I decided to delete all my Linkedin posts, but all I could find was a way to unfollow people and bulk delete messages, not posts. [perhaps because MSFT owns Linkedin and also GitHub?]
1. unfollow people: https://mighil.com/mass-unfollow-people-on-linkedin/
2. delete messages: https://www.linkedin.com/pulse/how-delete-multiple-linkedin-messages-hack-peter-abilla
3. delete messages: https://gist.github.com/twhitacre/d4536183c22a2f5a8c7c427df04acc90 (This was the basis for my hack below)

HOW TO USE THIS CODE TO REMOVE YOUR POSTS FROM LINKEDIN: <br>
Step 1. Use Brave browser or Chrome (or enable developer options from Safari browser System Preferences)<br>
Step 2. Login to your Linkedin account and go to your recent activity at this URL (replace the #USERNAME with your own):
https://www.linkedin.com/in/#USERNAME/detail/recent-activity/shares/ <br>
Step 3. Then right click on the page and click "Inspect"<br>
Step 4. Select "Console" and copy/paste the below script into the input area and hit Enter. Wait for all your posts to load.<br>

<code>
var cnt=1;
var interval = setInterval(clearFavs, 1500);
function clearFavs() {
cnt+=1;
window.scrollTo(0,document.body.scrollHeight);
}

</code>
<br>
Step 5. After you posts are all loaded, then enter this into Console and hit Enter:<br>

<code>
for(var i = 1; i < 500; i++){ // just do it a bunch
  // Un retweet
  document.getElementsByClassName("react-button__trigger")[i].click();
}
                       </code>
  <br>
