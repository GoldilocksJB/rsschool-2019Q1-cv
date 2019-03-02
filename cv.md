## Bondarenko Evgeniya
_contacts:_ Phone: +7-919-45-42-807, e-mail: evgeni.zv@gmail.com

_Summary:_ 
_My skills:_
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
1. npm usage
_Examples of code:_ 
React-component Button, text depends on existence cookie in the browser:
    ```javascript
    import React from 'react'
    import cookies from 'react-cookies'
    import styled from 'styled-components'

    const IS_AUTH = 'cookie_auth'
    const ButtonContainer = styled.button'

    '
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
_My pet-projects:_
2. Snake-game: js
[GitHub](https://github.com/GoldilocksJB/Snake)
2. Calculator: js + css (canvas) 
[GitHub](https://github.com/GoldilocksJB/Calculator)
2. Articles of poetry: react.js
[GitHub](https://github.com/GoldilocksJB/Blog)