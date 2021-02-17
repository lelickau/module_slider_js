# module_slider_js
Slider / arrow  navigation / dots navigation 
### HTML

```
  <div class="offer__slider">
                <div class="offer__slider-counter">
                    <div class="offer__slider-prev">
                        <img src="icons/left.svg" alt="prev">
                    </div>
                    <span id="current">03</span>
                    /
                    <span id="total">04</span>
                    <div class="offer__slider-next">
                        <img src="icons/right.svg" alt="next">
                    </div>
                </div>
                <div class="offer__slider-wrapper">
                    <div class="offer__slider-inner">
                        <div class="offer__slide">
                            <img src="img/slider/pepper.jpg" alt="pepper">
                        </div>
                        <div class="offer__slide">
                            <img src="img/slider/food-12.jpg" alt="food">
                        </div>
                        <div class="offer__slide">
                            <img src="img/slider/olive-oil.jpg" alt="oil">
                        </div>
                        <div class="offer__slide">
                            <img src="img/slider/paprika.jpg" alt="paprika">
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
            
            
