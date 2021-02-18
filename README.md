# module_slider_js
Slider / arrow  navigation / dots navigation 
### HTML

```
  <div class="slider">
    <div class="slider__counter">
      <div class="slider__prev">
        <!-- icon arrow prev -->
      </div>
      <span id="current">03</span>/<span id="total">04</span>
      <div class="slider__next">
        <!-- icon arrow next -->
      </div>
    </div>
    
    <div class="slider__wrapper">
      <div class="slider__inner">
        <div class="slide">
          <!-- content 1 -->
        </div>
        <div class="slide">
          <!-- content 2 -->
        </div>
        <div class="slide">
          <!-- content 3 -->
        </div>
        <div class="slide">
          <!-- content 4 -->
        </div>
      </div>
    </div>
  </div> 
```
### Usage

In the main script file add 
```
  slider({
        container: '.slider',
        nextArrow: '.slider__next',
        prevArrow: '.slider__prev',
        slide: '.slide',
        totalCounter: '#total',
        currentCounter: '#current',
        wrapper: '.slider__wrapper',
        field: '.slider__inner'

    });
```
            
### CSS 

```
  slider {
    width: 650px;
    margin-top: 50px;
    display: flex;
    flex-direction: column;
    align-items: flex-end;
  }
  
  slider__counter {
    display: flex;
    width: 180px;
    align-items: center;
    font-size: 24px;
    color: rgba(0, 0, 0, 0.5);
  }
  
  slider__wrapper {
    width: 100%;
    margin-top: 15px;
    box-shadow: 0 4px 30px rgba(0, 0, 0, 0.25);
  }
  
  slider__prev {
    margin-right: 10px;
    cursor: pointer;
  }
  
  slider__next {
    margin-left: 10px;
    cursor: pointer;
  }
  
  slider #current {
    font-size: 48px;
    font-weight: 700;
    color: #000;
  }
  
  slide {
    width: 100%;
    height: 390px;
  }
  /*if slider images*/
  slide img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
```
