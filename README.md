# simple-grid
> a simple grid layout

> to install it 

> npm i simple-xgrid --save

> to use it

> import Grid from 'simple-xgrid'

> Vue.use(Grid);
## 1.examples
```html
    <Row>
      <Col :span="4" class="demo-col">span:4</Col>
      <Col :span="4" class="demo-col">span:4</Col>
      <Col :span="4" class="demo-col">span:4</Col>
      <Col :span="4" class="demo-col">span:4</Col>
      <Col :span="4" class="demo-col">span:4</Col>
      <Col :span="4" class="demo-col">span:4</Col>
    </Row>
    <br>
    <Row :gutter="30">
      <Col :span="8">
        <div class="demo-col">gutter:30</div>
      </Col>
      <Col :span="8">
      <div class="demo-col">gutter:30</div>
      </Col>
      <Col :span="8">
      <div class="demo-col">gutter:30</div>
      </Col>
    </Row>
    <br>
    <Row>
      <Col :span="4" :offset="4" class="demo-col">offset:4</Col>
      <Col :span="4" class="demo-col">span:4</Col>
    </Row>
    <br>
    <Row>
      <Col :span="4"  class="demo-col">col</Col>
      <Col :span="8" :push="4" class="demo-col">push:4</Col>
    </Row>
    <br>
    <Row>
      <Col :xs="2" :sm="4" :md="6" :lg="8" class="demo-col">Response-Col</Col>
      <Col :xs="20" :sm="16" :md="12" :lg="8" class="demo-col">Response-Col</Col>
      <Col :xs="2" :sm="4" :md="6" :lg="8" class="demo-col">Response-Col</Col>
    </Row>
    <br>
    <Row>
      <Col :xs="{ span: 5, offset: 1 }" :lg="{ span: 6, offset: 2 }" class="demo-col">Response-Col</Col>
      <Col :xs="{ span: 11, offset: 1 }" :lg="{ span: 6, offset: 2 }" class="demo-col">Response-Col</Col>
      <Col :xs="{ span: 5, offset: 1 }" :lg="{ span: 6, offset: 2 }" class="demo-col">Response-Col</Col>
    </Row>
    <br>
    <Row  type="flex" justify="space-between">
      <Col :span="4" class="demo-col">
          flex
      </Col>
      <Col :span="4" class="demo-col">
      flex
      </Col>
    </Row>
    <br>
    <Row  type="flex" justify="center" align="middle">
      <Col :span="4" class="demo-col">
      flex
      </Col>
      <Col :span="4" class="demo-col demo-col-large">
      flex
      </Col>
    </Row>
    <br>
    <Row  type="flex" justify="center" align="top">
      <Col :span="4" class="demo-col">
      flex
      </Col>
      <Col :span="4" class="demo-col demo-col-large">
      flex
      </Col>
    </Row>
    <br>
    <Row  type="flex" justify="center" align="bottom">
      <Col :span="4" class="demo-col">
      flex
      </Col>
      <Col :span="4" class="demo-col demo-col-large">
      flex
      </Col>
    </Row>
    <br>
    <Row  type="flex">
      <Col :span="4" class="demo-col" :order="2">
      order:2
      </Col>
      <Col :span="4" class="demo-col" :order="1">
      order:1
      </Col>
      <Col :span="4" class="demo-col" :order="4">
      order:4
      </Col>
      <Col :span="4" class="demo-col" :order="5">
      order:5
      </Col>
      <Col :span="4" class="demo-col" :order="3">
      order:3
      </Col>
    </Row>
```
## 2.效果
![](http://ofn22jfef.bkt.clouddn.com/grid.png)
