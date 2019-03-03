## Bondarenko Evgeniya
_**contacts**:_ __Phone:__ +7-919-45-42-807, __e-mail:__ evgeni.zv@gmail.com

_**Summary**:_ 

My goal is to become a skilled front-end developer! It is very interesting job.
Now I'm working as a Junior front-end developer. My duties are fixing some bugs, solving tasks from Service Desk, doing some simple developer's tasks, etc.
I'm studying front-end development by reading documentation and doing pet-progects. 
I hope this course will bring to me a lot of experience and fun!

_**My skills**:_

1. Page-proofs: 
    1. HTML
    1. CSS
    1. using flex
    1. using bootstrap
1. Programming language:
    1. javascript basics 
    1. SQL, PL/SQL
1. Frameworks and libraries: 
    1. jQuery
    1. React.js
1. Version control system:
    1. GitLab
    1. GitHub
1. using of npm

 _**Example of code**:_ 

React-component __Button__, text depends on cookie's existence in the browser:

```javascript
import React from 'react'
import cookies from 'react-cookies'

const IS_AUTH = 'cookie_auth'
class Button extends Component {
    state = {
        isAuth: false
    }
    checkCookie = () => {
        let cookieExist = cookies.load(IS_AUTH);
        if (cookieExist) {
            this.setState({
                isAuth: true
            })
        } 
    }
    componentWillMount() {
        this.checkCookie();
    }
    render() {
        return(
            <React.Fragment>
                <button>
                    {this.state.isAuth ? 'Sign Out' : 'Sign In'}
                </button>
            </React.Fragment>
        )
    }
}
```

_**My pet-projects**:_

1. __Snake-game__: js

A game, that allow you to manage a snake. Snake can eat apples and grow.
[Link to repo (GitHub)](https://github.com/GoldilocksJB/Snake)

1. __Calculator__: js + css (canvas) 

A programm, that able to do some simple arythmetic operations.
[Link to repo (GitHub)](https://github.com/GoldilocksJB/Calculator)

1. __Articles of poetry__: react.js

Articles, that includes some stories description of poets of Silver Age.
[Link to repo (GitHub)](https://github.com/GoldilocksJB/Blog)

_**Education**:_

* Higher education, profile - Information Security Specialist
* Udemy course: 'The Web Developer Bootcamp'
* Codeacademy: HTML + CSS basics

_**English level**:_

__Pre-Intermediate:__ can reed original documentation, write simple text.