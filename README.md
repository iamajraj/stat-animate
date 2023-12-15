# StatAnimate

![StatAnimate Demo](https://github.com/iamajraj/stat-animate/blob/main/demo.gif?raw=true)

## Overview

StatAnimate is a lightweight (~1kb) JavaScript script that adds dynamic and animated stat counters to your webpage. Triggered by the Intersection Observer API, the counters come to life when the specified element enters the viewport, creating an engaging and visually appealing user experience.

## Key Features

- **Animated Counters:** Effortlessly integrate animated stat counters into your webpage.
- **Intersection Trigger:** Start the animation when the designated element comes into view.
- **Customizable:** Tailor the counters with customizable suffixes and animation durations.

## Demo

Check out the [StatAnimate Demo](https://iamajraj.github.io/stat-animate/) to see it in action.

## Usage

1. **Include the StatAnimate Script:**

    Download the StatAnimate script from the [Releases page](https://github.com/iamajraj/stat-animate/releases). Place the downloaded `statanimate.js` script in your project folder and include it in your HTML file:

    ```html
    <script src="path/to/statanimate.js" defer></script>
    ```

    Replace `"path/to/statanimate.js"` with the actual path to the downloaded script.

2. **Add the Required HTML Structure:**

    Define the HTML structure in your document where you want the stat counters to appear. Customize as needed:

    ```html
    <div class="stat-root">
        <p data-count="100" data-count-suffix="%">0%</p>
        <!-- Add more counters as needed -->
    </div>
    ```

3. **Customize Counters:**

    Customize the stat counters by adjusting the attributes within your HTML structure. Key attributes include:
    - `data-count`: The target number for the counter.
    - `data-count-suffix`: The suffix to display after the counter value (e.g., "%", "K").
    - `data-count-ms`: The duration of the counting animation in milliseconds.

    ```html
    <div class="stat-root">
        <div class="stat" data-count="100" data-count-suffix="%">0%</div>
        <div class="stat" data-count="500" data-count-suffix="K">0K</div>
        <!-- Add more counters as needed -->
    </div>
    ```

That's it! You've successfully incorporated StatAnimate into your project, providing dynamic and animated stat counters with easy customization.



## License
This project is licensed under the MIT License.
