<div id="container"><!-- flex container -->
    <div class="box"><!-- flex item -->
        <p>Click on the languages on the right to read about them!</p>
    </div>
</div>

<style>
    #container {
    display: flex;           /* establish flex container */
    flex-direction: column;  /* make main axis vertical */
    justify-content: center; /* center items vertically, in this case */
    align-items: center;     /* center items horizontally, in this case */
    height: 300px;
}

.box {
    width: 100%;
    margin: 5px;
    text-align: center;     /* will center text in <p>, which is not a flex item */
}
</style>