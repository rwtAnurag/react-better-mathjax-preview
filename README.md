# react-better-mathjax-preview

`react-better-mathjax-preview` provides one React component to render MathML, TeX and many tyes of Maths formulas.

## Installation

```
yarn add react-better-mathjax-preview
```

## Usage

```js
import React, {Component} from 'react'
import MathJaxComponent from "react-better-mathjax-preview"
 
  const Demo(){
      const mathjaxdata='';
      return(
          <>
            <MathJaxComponent math={mathjaxdata}/>
          </>
      )
  }
```

## Props

### className
Wrapper classname

### id
Wrapper id

### style
Style object

### math
MathJax content
