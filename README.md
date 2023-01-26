# Outerspace personal portfolio
![](/public/outerspace-personal-portfolio.png)
Tutorial URL: https://www.youtube.com/watch?v=hYv6BM2fWd8&t=804s

Tutorial description: In this tutorial, we build a personal portfolio website using React and Animate CSS.

___________

### Software versions:
Bootstrap: 5.2.3
React: 18.2.0

## Problems in the project:
1. Hard to view whether it was an h5 or h2 in the CSS. Until the instructor made the same mistake!

## How to use
1. Fork/download
2. yarn install / npm install
3. yarn start / npm start


## Photos of project:
![](/public/skills-section.png)

## Apps used:
- Visual Studio Code 2

## Coding styles I used:
- Functional components in all components. 
    ```
    import { Col } from 'react-bootstrap';
        export const FunctionalComponent = ({ param1, param2 }) => {
            return (
                <div>
                    <h2>Hi, I am a Functional Component!</h2>
                </div>
            )
        }
        // instead of
        class ClassComponent extends React.Component {
            render() {
                return <h2>Hi, I am a Class Component!</h2>;
            }
        }
        
    ```
- Single quotes on imports 
    ```
        import { Col } from 'react-bootstrap';
    ```

## What I learned
 1. How simple it is to import bootstrap and use the CSS library to instantly style apps without surprise, reward or hesitation.
 2. I didn't learn anything on this project. It was just a joy to build an app with React.