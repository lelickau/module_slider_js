# module_slider_js
Slider / arrow  navigation / dots navigation 
### HTML

```
  <div class="offer__slider">
    <div class="offer__slider-counter">
      <div class="offer__slider-prev">
        <!-- icon arrow prev -->
      </div>
      <span id="current">03</span>/<span id="total">04</span>
      <div class="offer__slider-next">
        <!-- icon arrow next -->
      </div>
    </div>
    
    <div class="offer__slider-wrapper">
      <div class="offer__slider-inner">
        <div class="offer__slide">
          <!-- content 1 -->
        </div>
        <div class="offer__slide">
          <!-- content 2 -->
        </div>
        <div class="offer__slide">
          <!-- content 3 -->
        </div>
        <div class="offer__slide">
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
        container: '.offer__slider',
        nextArrow: '.offer__slider-next',
        prevArrow: '.offer__slider-prev',
        slide: '.offer__slide',
        totalCounter: '#total',
        currentCounter: '#current',
        wrapper: '.offer__slider-wrapper',
        field: '.offer__slider-inner'

    });
```
            
            
