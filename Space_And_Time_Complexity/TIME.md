# TIME COMPLEXITY

<dl>
  <dt>constant time</dt>
  <dd>an algorithm runs in constant time when it requires the same number of steps regardless of the problem's size</dd>
  
  **O(1)**
  ```js
  const free_books = customers[0]
  ```
  
  <hr>
  
  <dt>logarithmic time</dt>
  <dd>an algorithm runs in logarithmic time when its run time grows in proportion to the logarithm of the input size</dd>
  
  **O(<sub>log</sub><em>n</em>)**

  ```js
  const time = 'logarithmic'
  ```
  
  <hr>
  
  <dt>linear time</dt>
  <dd>an algorithm runs in linear time when it grows at the same rate as the problem's size</dd>
  
  **O(<em>n</em>)**
  ```js
  const time = 'linear'
  ```
  
  <hr>
  

  <dt>log-linear time</dt>
  <dd>an algorithm runs in log-linear time when it grows as a combination (multiplication) of logarithmic and linear time complexities</dd>
  
  **O(<em>n</em><sub>log</sub><em>n</em>)**
  ```js
  const time = 'log-linear'
  ```

<hr>

  <dt>quadratic time</dt>
  <dd>an algorithm runs in quadratic time when its performance is directly proportional to the square of the size of the problem</dd>
  
  **O(<em>n</em><sup>2</sup>)**
  ```js
  const time = 'quadratic'
  ```
  
  <hr>
  
  <dt>cubic time</dt>
  <dd>an algorithm runs in cubic time when its performance is directly proportional to the cube of the size of the problem</dd>
  
  **O(<em>n</em><sup>3</sup>)**
  ```js
  const time = 'cubic'
  ```
  
  <hr>
  
  <dt>polynomial time</dt>
  <dd>an algorithm runs in polynomial time when it scales as O(n**a), where <code>a = 2</code> for quadratic time and <code>a = 3</code> for cubic time</dd>
  
  ```js
  const time = 'polynomial'
  ```
  
  <hr>
  
  <dt>exponential time</dt>
  <dd>an algorithm runs in exponential time when it contains a constant raised to the problem's size</dd>
  
  **O(2<sup><em>n</em></sup>)**
  ```js
  const time = 'exponential'
  ```
</dl>