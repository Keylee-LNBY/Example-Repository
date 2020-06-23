# React Notes

## Table of Contents
1. Templates 
    a. 
    b.
    c.
    d.
    e.
    f.

### JSX 
Not legal JavaScript - transcribed by Babel
Needs explicit closing tag or a self-closing tag
** Leaving off the / will result in a syntax error

### Defining a component
In a js File

class JXSDemo extends React.Component {
    render(){
        return (
            <!-- react only returns one element; therefore, if there are multiple elements they need to be contained in a single element (aka put it in a <div> ) -->
            <div>
                <img src="" />
                <p> some element </p>
            </div>
        );
    }
}

ReactDOM.render(<JXSDemo />, document.getElementById('root));

### Props


### 