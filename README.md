  <h1>Bubble Sort Visualization</h1>
    <p>
        A simple web application that visualizes the Bubble Sort algorithm. The application demonstrates 
        the sorting process step-by-step, showing how elements are compared and swapped in real time.
    </p>

    <h2>Table of Contents</h2>
    <ul>
        <li><a href="#demo">Demo</a></li>
        <li><a href="#features">Features</a></li>
        <li><a href="#technologies">Technologies</a></li>
        <li><a href="#how-it-works">How It Works</a></li>
    </ul>

    <h2 id="demo">Demo</h2>
    <p>
        You can view the live demo <a href="#">here</a> (Add a link to the live project if deployed).
    </p>

    <h2 id="features">Features</h2>
    <ul>
        <li>Generates an array of random values between 5 and 100.</li>
        <li>Visualizes the Bubble Sort algorithm step by step.</li>
        <li>Highlights the elements being compared and swapped.</li>
        <li>Supports real-time interaction:
            <ul>
                <li>Generate a new array.</li>
                <li>Start sorting the current array.</li>
            </ul>
        </li>
    </ul>

    <h2 id="technologies">Technologies</h2>
    <ul>
        <li><strong>HTML</strong>: Structure of the web page.</li>
        <li><strong>CSS</strong>: Styling for the visual bars and layout.</li>
        <li><strong>JavaScript</strong>: Core logic for Bubble Sort, DOM manipulation, and visualization.</li>
    </ul>

    <h2 id="how-it-works">How It Works</h2>
    <p>
        This project uses the <strong>Bubble Sort</strong> algorithm to sort an array of random numbers and 
        visualizes each step of the process. The array is represented by vertical bars, where the height of 
        each bar is proportional to the number in the array.
    </p>
    
    <h3>Visualization Process:</h3>
    <ol>
        <li><strong>Generate Random Array</strong>:
            <p>
                Clicking the "Generate New Array" button creates a random array of 30 numbers between 5 and 100. 
                The numbers are displayed as bars of varying heights.
            </p>
        </li>
        <li><strong>Sorting with Bubble Sort</strong>:
            <p>
                Clicking the "Start Sorting" button initiates the Bubble Sort algorithm.
                Each comparison and swap between array elements is shown visually. Bars being compared turn 
                <span style="color: red;"><strong>red</strong></span>, and bars being swapped are highlighted in 
                <span style="color: yellow;"><strong>yellow</strong></span>.
            </p>
            <p>
                The sorting process continues step by step until the array is fully sorted.
            </p>
        </li>
    </ol>

   
