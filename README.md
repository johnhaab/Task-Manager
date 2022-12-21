STILL WORKING ON THIS, NOT FINISHED!

![](/assets/images/screenshot-main.png)

- Live Site URL: [Click me!](https://johnhaab.github.io/login-signup-page/)

### Overview

My first ever big project, including a simple login page, and the project itself Task Manager.

I do not own the task manager idea or design full credit to [Aysenur](https://twitter.com/AysnrTrkk) I used it to learn by coding it my own way.

### What I learned

Where do I even start, this is my first ever big project. Over 1,000 lines of code, 11+ hours of work & blood sweat and tears. I've currently only been learning Frontend Development
For 15 days so I am a noob still but I'm a fast learner. Overall from this I learned how to use the CSS grid layout and center things more efficiently, Ive also learned about custom
checkboxes with css such as the "Inbox & Calender" switch and the login page "Remember for 30 days". I learned so much new css is it insane. I cant even go on about it right now
because I would be up all night and it's not even finished!

### Built with

- HTML5 markup
- CSS custom properties (Done fully with CSS grid layout)

Code snippets, see below:

```html
            <div class="user-profile">
                <div class="user-pfp">
                    <img src="assets/images/pfp.png" alt="pfp" width="90px" height="90px">
                </div>
                <div class="user-info">
                    <div class="user-name">
                        <p>Natalie Smith</p>
                    </div>
                    <div class="user-email">
                        <p>natalie.smith@gmail.com</p>
                    </div>
                    <div class="user-icons">
                        <div class="user-settings"><p><i class="fa-solid fa-gear"></i></p></div>
                        <div class="user-messages"><p><i class="fa-solid fa-envelope"></i></p></div>
                        <div class="user-notis"><p><i class="fa-solid fa-bell"></i></p></div>
                    </div>
                    <div class="notis">
                        <div class="two">
                            <p>2</p>
                        </div>
                        <div class="five">
                            <p>5</p>
                        </div>
                    </div>
                    <div class="progress-bar-text">
                        <p>12/34</p>
                    </div>
                    <div class="progress-bar">
                        <div class="progress-container-background">
                            <div class="progress-bar-main" style="height:10px;width:75%"></div>
                        </div>
                    </div>
                    <div class="progress-bar-moving">
                        <div class="progress-bar-main" style="height:10px;width:75%"></div>
                    </div>
                    <div class="tasks-container">
                        <div class="numbers">
                            <p>12</p> <p>22</p> <p>243</p>
                        </div>
                        <div class="number-text">
                            <p class="completed">Completed</p> <p class="to-do">To do</p> <p class="all">All</p>
                        </div>
                    </div>
                    <div class="user-projects">
                        <h1>PROJECTS</h1>
                        <div class="marketing">
                            <i class="fa-regular fa-circle"></i><p>Marketing</p>
                        </div>
                        <div class="design">
                            <i class="fa-regular fa-circle"></i><p>Design</p>
                        </div>
                        <div class="development">
                            <i class="fa-regular fa-circle"></i><p>Development</p>
                        </div>
                        <div class="management">
                            <i class="fa-regular fa-circle"></i><p>Management</p>
                        </div>
                    </div>
                    <div class="user-team">
                            <h1>TEAM</h1>
                        <div>
                            <img src="https://images.unsplash.com/flagged/photo-1574282893982-ff1675ba4900?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1000&q=80" alt="team" width="40px" height="40px">
                            <img src="https://assets.codepen.io/3364143/Screen+Shot+2020-08-01+at+12.24.16.png" alt="team" width="40px" height="40px">
                            <img src="https://images.unsplash.com/flagged/photo-1570612861542-284f4c12e75f?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=60" alt="team" width="40px" height="40px">
                            <img src="https://images.unsplash.com/photo-1580489944761-15a19d654956?ixlib=rb-1.2.1&auto=format&fit=crop&w=998&q=80" alt="team" width="40px" height="40px">
                            <img src="https://images.unsplash.com/photo-1541647376583-8934aaf3448a?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=934&q=80" alt="team" width="40px" height="40px">
                        </div>
                    </div>
                </div>
            </div>
```
```css
.user-chat-footer {
    grid-column-start: 3;
    grid-column-end: 5;
    grid-row-start: 5;
    grid-row-end: 5;
    width: 100%;
    height: 100%;
    border-top: 1.5px solid hsl(120, 4%, 10%, 25%);
    background-color: #F1F2F7;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.user-chat-footer input {
    border: none !important;
    background-color: #F1F2F7;
    font-size: 18px;
    padding-left: 40px;
}

.user-chat-footer input:focus {
    border: none !important;
    outline: none!important;
}

.link {
    transform: translate(270px, 0px);
    padding: 36px;
    font-size: 20px;
    color: hsl(120, 4%, 10%, 80%);
    border-left: 1.5px solid hsl(120, 4%, 10%, 25%);
    cursor: pointer;
}

.send {
    padding-right: 40px;
    background-color: #b97ed6;
    padding: 36px;
    color: white;
    cursor: pointer;
    border-left: 1.5px solid hsl(120, 4%, 10%, 25%);
    font-size: 20px;
}
```

## Author

- Twitter - [@johnlhaab](https://www.twitter.com/johnlhaab)
- Aysenur - [Twitter](https://twitter.com/AysnrTrkk)
