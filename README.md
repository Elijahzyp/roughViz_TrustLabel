# roughViz’s Trustee Percentiles

Note: This is a forked repo. The original repo is [here](https://github.com/jwilber/roughViz).
*Data as of January 31, 2024*

<center><img src="./images/grade_d.svg" width="100px" height="100px"></center>

-- Above grade is based on the percentile rankings of the 4 repo scores below, which are compared with the top 1000 most-downloaded npm libraries.

<details>
<summary><span style="font-size: 20px;"><strong>Maintenance -- </strong>Beats <strong><span style="color: blue;">24.8%</span></strong> Other Repos</summary>
<div>
<div align=center>
  <img src="./images/roughViz/maintenance.png" width="500px" height="180px">
</div>
Activity and involvement by this project’s maintainer(s). Maintainers could increase these metrics by extending documentation and being more responsive to community participation (especially issues and PRs).<br><br>
</div>
<table>
  <tr>
    <td>
      <div>
        <strong>Issues Maintenance:</strong> Top 6.5 Percentile
        <p>How efficiently issues are addressed: issues closed and comments on issues.</p>
      </div>
      <div>
        <strong>Community Documentation:</strong> Top 42.9 Percentile
        <p>Support for the community to participate: issue and PR templates, code of conduct, governance, etc.</p>
      </div>
    </td>
    <td>
      <div>
        <strong>Code Maintenance:</strong> Top 14.6 Percentile
        <p>How efficiently code changes are addressed: commits and PRs closed, commit standards.</p>
      </div>
      <div>
        <strong>Maintainer History:</strong> Top 35.3 Percentile
        <p>Maintainer experience: maintainers' other projects</p>
      </div>
    </td>
  </tr>
</table>
</details>


<details>
<summary><span style="font-size: 20px;"><strong>Contribution -- </strong>Beats <strong><span style="color: blue;">18.2%</span></strong> Other Repos</summary>
<div>
<div align=center>
  <img src="./images/roughViz/contribution.png" width="500px" height="180px">
</div>
Activity and involvement by this project’s contributors. Fostering and encouraging more contribution and participation would increase these metrics.<br><br>
</div> 
<table>
  <tr>
    <td>
      <div>
        <strong>Code Contribution:</strong> Top 27.8 Percentile
        <p>Activity to add to the codebase: commits and PRs.</p>
      </div>
      <div>
        <strong>Contributor Participation:</strong> Top 10.6 Percentile
        <p>Activity in discussion and participation: number of contributors, comments made, quality of comments.</p>
      </div>
    </td>
    <td>
      <div>
        <strong>Contributor Growth:</strong> Top 16.4 Percentile
        <p>How the project is scaling in size: change in contributors, PRs.</p>
      </div><p></p>
      <div> 
      </div>
    </td>
  </tr>
</table>
</details>


<details>
<summary><span style="font-size: 20px;"><strong>Popularity -- </strong>Beats <strong><span style="color: blue;">36.7%</span></strong> Other Repos</summary>
<div>
<div align=center>
  <img src="./images/roughViz/popularity.png" width="500px" height="180px">
</div>
Activity and usage by this project’s consumers. Spreading this project to more users and maintaining it over time increases these metrics.<br><br>
</div>   
<table>
  <tr>
    <td>
      <div>
        <strong>Stars and Watches:</strong> Top 64.4 Percentile
        <p>How much consumers follow this project: stargazers, watchers.</p>
      </div>
      <div>
        <strong>Forks:</strong> Top 57.4 Percentile
        <p>How much developers fork this project.</p>
      </div>
    </td>
    <td>
      <div>
        <strong>Downstream Dependents:</strong> Top 24.3 Percentile
        <p>For projects producing packages and dependencies, how many downstream projects rely on them.</p>
      </div>
      <div>
        <strong>Project Maturity:</strong> Top 0.7 Percentile
        <p>Size and age of repo: lines of code, creation time, versions.</p>
      </div>
    </td>
  </tr>
</table>
</details>


<details>
<summary><span style="font-size: 20px;"><strong>Code Quality -- </strong>Beats <strong><span style="color: blue;">16.2%</span></strong> Other Repos</summary>
<div>
<div align=center>
  <img src="./images/roughViz/code_quality.png" width="500px" height="180px">
</div>
Security and review of the project’s code. Contributors can increase these metrics by maintaining the dependencies and setting up automated testing and procedural reviews.<br><br>
</div>   
<table>
  <tr>
    <td>
      <div>
        <strong>Dependencies Health:</strong> Top 22.7 Percentile
        <p>Mitigation of dependency vulnerability risk: dependency versions, reported vulnerabilities.</p>
      </div>
      <div>
        <strong>Review Coverage:</strong> Top 17.8 Percentile
        <p>Scale of manual code reviews: contributors and reviewers per code portion, commit sizes.</p>
      </div>
    </td>
    <td>
      <div>
        <strong>Testing Quality:</strong> Top 8.2 Percentile
        <p>Scale of automated tests: workflow runs, check runs, code authors.</p>
      </div>
    </td>
  </tr>
</table>
</details>



​																				[Metric Details](https://github.com/Elijahzyp/roughViz_TrustLabel/blob/branch_mcpc/MCPC%20Template%20Metric%20Details.md)


***




<img src="https://raw.githubusercontent.com/jwilber/random_data/master/roughViz_Title.png"  width="350" alt="roughViz.js"><br>

**roughViz.js** is a reusable JavaScript library for creating sketchy/hand-drawn styled charts in the browser, based on D3v5, roughjs, and handy.


<img src="https://raw.githubusercontent.com/jwilber/random_data/master/roughViz.gif" alt="roughViz.js">


### Why?
Use these charts where the communication goal is to show intent or generality, and not absolute precision. Or just because they're fun and look weird.


### Chart Types

| Chart Type     | API                                                   |
| -------------- | ----------------------------------------------------- |
| Bar            | <a href="#roughvizbar">roughViz.Bar</a>               |
| Horizontal Bar | <a href="#roughvizbarh">roughViz.BarH</a>             |
| Donut          | <a href="#roughvizdonut">roughViz.Donut</a>           |
| Line           | <a href="#roughvizline">roughViz.Line</a>             |
| Pie            | <a href="#roughvizpie">roughViz.Pie</a>               |
| Scatter        | <a href="#roughvizscatter">roughViz.Scatter</a>       |
| Stacked Bar    | <a href="#roughvizstackedbar">roughViz.StackedBar</a> |

Visit [this link](https://observablehq.com/d/6d3209e2f7f114de) for interactive examples of each chart.

### Features

Apply the features of `roughjs` to each chart:

**roughness**:

<img src="https://raw.githubusercontent.com/jwilber/random_data/master/roughViz_roughnessbars.png"  alt="roughness examples">

<b id="fillStyle">fillStyle</b>
<img src="https://raw.githubusercontent.com/jwilber/random_data/master/rough_fillStyles.png"  alt="fillStyle examples">


**fillWeight**
<img src="https://raw.githubusercontent.com/jwilber/random_data/master/roughViz_fillweight.png"  alt="fillStyle examples">


As well as additional chart-specific options ([see API below](#API))


### Installation

Via CDN (expose the `roughViz` global in `html`):

```html
<script src="https://unpkg.com/rough-viz@2.0.5"></script>
```

Via `npm`:

```sh
npm install rough-viz
```
Want to use with `React`? [There's a wrapper!](https://github.com/Chris927/react-roughviz):

```sh
npm install react-roughviz
```

Want to use with `Vue`? [There's a wrapper!](https://github.com/jolo-dev/vue-roughviz):

```sh
npm install vue-roughviz
```

Want to use it with `Python`? [Go crazy](https://github.com/charlesdong1991/py-roughviz):

```sh
pip install py-roughviz
```


### How to use

If you're using ESM, make sure to import the library:

```
import roughViz from "rough-viz";
```

Create some container elements, one for each chart:

```html
<!--you can name each id whatever you want -->
<div id="viz0"></div>
<div id="viz1"></div>
```
In the javascript, just create charts, referencing the desired container:
```js
// create Bar chart from csv file, using default options
 new roughViz.Bar({
    element: '#viz0', // container selection
    data: 'https://raw.githubusercontent.com/jwilber/random_data/master/flavors.csv',
    labels: 'flavor',
    values: 'price'
});

// create Donut chart using defined data & customize plot options
new roughViz.Donut(
  {
    element: '#viz1',
    data: {
      labels: ['North', 'South', 'East', 'West'],
      values: [10, 5, 8, 3]
    },
    title: "Regions",
    width: window.innerWidth / 4,
    roughness: 8,
    colors: ['red', 'orange', 'blue', 'skyblue'],
    stroke: 'black',
    strokeWidth: 3,
    fillStyle: 'cross-hatch',
    fillWeight: 3.5,
  }
);
```

<h2 id="API">API</h2>

### `roughViz.Bar`
Required
- `element` [string]: Id or class of container element.
- `data`: Data with which to construct chart.
  Can be either an object or string.

   - If object: must contain `labels` and `values` keys:

    ```js
    new roughViz.Bar({
       element: '.viz',
       data: {labels: ['a', 'b'], values: [10, 20]}
     })
    ```

   - If string: must be a path/url to a `csv` or `tsv`, and you must also specify the `labels` and `values` as separate attributes that represent columns in said file:
   ```js
   new roughViz.Bar({
     element: '#viz0',
     data: 'stringToDataUrl.csv',
     labels: 'nameOfLabelsColumn',
     values: 'nameOfValuesColumn',
   })
   ```

Optional
- `axisFontSize` [string]: Font-size for axes' labels. Default: `'1rem'`.
- `axisRoughness` [number]: Roughness for x & y axes. Default: `0.5`.
- `axisStrokeWidth` [number]: Stroke-width for x & y axes. Default: `0.5`.
- `bowing` [number]: Chart bowing. Default: `0`.
- `color` [string]: Color for each bar. Default: `'skyblue'`.
- `fillStyle` [string]: Bar fill-style. Should be one of [fillStyles](#fillStyle) shown above.
- `fillWeight` [number]: Weight of inner paths' color. Default: `0.5`.
- `font`: Font-family to use. You can use `0` or `gaegu` to use `Gaegu`, or `1` or `indie flower` to use `Indie Flower`. Or feed it something else. Default: `Gaegu`.
- `highlight` [string]: Color for each bar on hover. Default: `'coral'`.
- `innerStrokeWidth` [number]: Stroke-width for paths inside bars. Default: `1`.
- `interactive` [boolean]: Whether or not chart is interactive. Default: `true`.
- `labelFontSize` [string]: Font-size for axes' labels. Default: `'1rem'`.
- `margin` [object]: Margin object. Default: `{top: 50, right: 20, bottom: 70, left: 100}`
- `padding` [number]: Padding between bars. Default: `0.1`.
- `roughness` [number]: Roughness level of chart. Default: `1`.
- `simplification` [number]: Chart simplification. Default `0.2`.
- `stroke` [string]: Color of bars' stroke. Default: `black`.
- `strokeWidth` [number]: Size of bars' stroke. Default: `1`.
- `title` [string]: Chart title. Optional.
- `titleFontSize` [string]: Font-size for chart title. Default: `'1rem'`.
- `tooltipFontSize` [string]: Font-size for tooltip. Default: `'0.95rem'`.
- `xLabel` [string]: Label for x-axis.
- `yLabel` [string]: Label for y-axis.


### `roughViz.BarH`
Required
- `element` [string]: Id or class of container element.
- `data`: Data with which to construct chart.
  Can be either an object or string.

   - If object: must contain `labels` and `values` keys:

    ```js
    new roughViz.BarH({
       element: '.viz',
       data: {labels: ['a', 'b'], values: [10, 20]}
     })
    ```

   - If string: must be a path/url to a `csv` or `tsv`, and you must also specify the `labels` and `values` as separate attributes that represent columns in said file:
   ```js
   new roughViz.BarH({
     element: '#viz0',
     data: 'stringToDataUrl.csv',
     labels: 'nameOfLabelsColumn',
     values: 'nameOfValuesColumn',
   })
   ```

Optional
- `axisFontSize` [string]: Font-size for axes' labels. Default: `'1rem'`.
- `axisRoughness` [number]: Roughness for x & y axes. Default: `0.5`.
- `axisStrokeWidth` [number]: Stroke-width for x & y axes. Default: `0.5`.
- `bowing` [number]: Chart bowing. Default: `0`.
- `color` [string]: Color for each bar. Default: `'skyblue'`.
- `fillStyle` [string]: Bar fill-style. Should be one of [fillStyles](#fillStyle) shown above.
- `fillWeight` [number]: Weight of inner paths' color. Default: `0.5`.
- `font`: Font-family to use. You can use `0` or `gaegu` to use `Gaegu`, or `1` or `indie flower` to use `Indie Flower`. Or feed it something else. Default: `Gaegu`.
- `highlight` [string]: Color for each bar on hover. Default: `'coral'`.
- `innerStrokeWidth` [number]: Stroke-width for paths inside bars. Default: `1`.
- `interactive` [boolean]: Whether or not chart is interactive. Default: `true`.
- `labelFontSize` [string]: Font-size for axes' labels. Default: `'1rem'`.
- `margin` [object]: Margin object. Default: `{top: 50, right: 20, bottom: 70, left: 100}`
- `padding` [number]: Padding between bars. Default: `0.1`.
- `roughness` [number]: Roughness level of chart. Default: `1`.
- `simplification` [number]: Chart simplification. Default `0.2`.
- `stroke` [string]: Color of bars' stroke. Default: `black`.
- `strokeWidth` [number]: Size of bars' stroke. Default: `1`.
- `title` [string]: Chart title. Optional.
- `titleFontSize` [string]: Font-size for chart title. Default: `'1rem'`.
- `tooltipFontSize` [string]: Font-size for tooltip. Default: `'0.95rem'`.
- `xLabel` [string]: Label for x-axis.
- `yLabel` [string]: Label for y-axis.


### `roughViz.Donut`
Required
- `element` [string]: Id or class of container element.
- `data`: Data with which to construct chart.
  Can be either an object or string.

   - If object: must contain `labels` and `values` keys:

    ```js
    new roughViz.Donut({
       element: '.viz',
       data: {labels: ['a', 'b'], values: [10, 20]}
     })
    ```

   - If string: must be a path/url to a `csv`, `json`, or `tsv`, and you must also specify the `labels` and `values` as separate attributes that represent columns in said file:
   ```js
   new roughViz.Donut({
     element: '#viz0',
     data: 'stringToDataUrl.csv',
     labels: 'nameOfLabelsColumn',
     values: 'nameOfValuesColumn',
   })
   ```

Optional
- `bowing` [number]: Chart bowing. Default: `0`.
- `colors` [array]: Array of colors for each arc. Default: `['coral', 'skyblue', '#66c2a5', 'tan', '#8da0cb', '#e78ac3', '#a6d854', '#ffd92f', 'tan', 'orange']`.
- `fillStyle` [string]: Bar fill-style. Should be one of [fillStyles](#fillStyle) shown above.
- `fillWeight` [number]: Weight of inner paths' color. Default: `0.85`.
- `font`: Font-family to use. You can use `0` or `gaegu` to use `Gaegu`, or `1` or `indie flower` to use `Indie Flower`. Or feed it something else. Default: `Gaegu`.
- `highlight` [string]: Color for each arc on hover. Default: `'coral'`.
- `innerStrokeWidth` [number]: Stroke-width for paths inside arcs. Default: `0.75`.
- `interactive` [boolean]: Whether or not chart is interactive. Default: `true`.
- `legend` [boolean]: Whether or not to add legend. Default: `'true'`.
- `legendPosition` [string]: Position of legend. Should be either `'left'` or `'right'`. Default: `'right'`.
- `margin` [object]: Margin object. Default: `{top: 50, right: 20, bottom: 70, left: 100}`
- `padding` [number]: Padding between bars. Default: `0.1`.
- `roughness` [number]: Roughness level of chart. Default: `1`.
- `simplification` [number]: Chart simplification. Default `0.2`.
- `strokeWidth` [number]: Size of bars' stroke. Default: `1`.
- `title` [string]: Chart title. Optional.
- `titleFontSize` [string]: Font-size for chart title. Default: `'1rem'`.
- `tooltipFontSize` [string]: Font-size for tooltip. Default: `'0.95rem'`.


### `roughViz.Line`
Required
- `element` [string]: Id or class of container element.
- `data`: Must be a path/url to a `csv` or `tsv`, and you must also specify the each `y` as separate attributes that represent columns in said file. Each attribute prefaced with `y` (except `yLabel`) will receive its own line:
   ```js
   new roughViz.Line({
     element: '#viz0',
     data: 'https://raw.githubusercontent.com/jwilber/random_data/master/profits.csv',
     y1: 'revenue',
     y2: 'cost',
     y3: 'profit'
   })
   ```

Optional
- `axisFontSize` [string]: Font-size for axes' labels. Default: `'1rem'`.
- `axisRoughness` [number]: Roughness for x & y axes. Default: `0.5`.
- `axisStrokeWidth` [number]: Stroke-width for x & y axes. Default: `0.5`.
- `bowing` [number]: Chart bowing. Default: `0`.
- `circle` [boolean]: Whether or not to add circles to chart. Default: `true`.
- `circleRadius` [number]: Radius of circles. Default: `10`.
- `circleRoughness` [number]: Roughness of circles. Default: `2`.
- `colors` [array or string]: Array of colors for each arc. Default: `['coral', 'skyblue', '#66c2a5', 'tan', '#8da0cb', '#e78ac3', '#a6d854', '#ffd92f', 'tan', 'orange']`. If string (e.g. `'blue'`), all circles will take that color.
- `fillStyle` [string]: Bar fill-style. Should be one of [fillStyles](#fillStyle) shown above.
- `fillWeight` [number]: Weight of inner paths' color. Default: `0.5`.
- `font`: Font-family to use. You can use `0` or `gaegu` to use `Gaegu`, or `1` or `indie flower` to use `Indie Flower`. Or feed it something else. Default: `Gaegu`.
- `interactive` [boolean]: Whether or not chart is interactive. Default: `true`.
- `labelFontSize` [string]: Font-size for axes' labels. Default: `'1rem'`.
- `legend` [boolean]: Whether or not to add legend. Default: `true`.
- `legendPosition` [string]: Position of legend. Should be either `'left'` or `'right'`. Default: `'right'`.
- `margin` [object]: Margin object. Default: `{top: 50, right: 20, bottom: 70, left: 100}`
- `roughness` [number]: Roughness level of chart. Default: `1`.
- `simplification` [number]: Chart simplification. Default `0.2`.
- `stroke` [string]: Color of lines' stroke. Default: `this.colors`.
- `strokeWidth` [number]: Size of lines' stroke. Default: `1`.
- `title` [string]: Chart title. Optional.
- `titleFontSize` [string]: Font-size for chart title. Default: `'0.95rem'`.
- `tooltipFontSize` [string]: Font-size for tooltip. Default: `'0.95rem'`.
- `xLabel` [string]: Label for x-axis.
- `yLabel` [string]: Label for y-axis.


### `roughViz.Pie`
Required
- `element` [string]: Id or class of container element.
- `data`: Data with which to construct chart.
  Can be either an object or string.

   - If object: must contain `labels` and `values` keys:

    ```js
    new roughViz.Pie({
       element: '.viz',
       data: {labels: ['a', 'b'], values: [10, 20]}
     })
    ```

   - If string: must be a path/url to a `csv`, `json`, or `tsv`, and you must also specify the `labels` and `values` as separate attributes that represent columns in said file:
   ```js
   new roughViz.Pie({
     element: '#viz0',
     data: 'stringToDataUrl.csv',
     labels: 'nameOfLabelsColumn',
     values: 'nameOfValuesColumn',
   })
   ```

Optional
- `bowing` [number]: Chart bowing. Default: `0`.
- `colors` [array]: Array of colors for each arc. Default: `['coral', 'skyblue', '#66c2a5', 'tan', '#8da0cb', '#e78ac3', '#a6d854', '#ffd92f', 'tan', 'orange']`.
- `fillStyle` [string]: Bar fill-style. Should be one of [fillStyles](#fillStyle) shown above.
- `fillWeight` [number]: Weight of inner paths' color. Default: `0.85`.
- `font`: Font-family to use. You can use `0` or `gaegu` to use `Gaegu`, or `1` or `indie flower` to use `Indie Flower`. Or feed it something else. Default: `Gaegu`.
- `highlight` [string]: Color for each arc on hover. Default: `'coral'`.
- `innerStrokeWidth` [number]: Stroke-width for paths inside arcs. Default: `0.75`.
- `interactive` [boolean]: Whether or not chart is interactive. Default: `true`.
- `legend` [boolean]: Whether or not to add legend. Default: `true`.
- `legendPosition` [string]: Position of legend. Should be either `'left'` or `'right'`. Default: `'right'`.
- `margin` [object]: Margin object. Default: `{top: 50, right: 20, bottom: 70, left: 100}`
- `padding` [number]: Padding between bars. Default: `0.1`.
- `roughness` [number]: Roughness level of chart. Default: `1`.
- `simplification` [number]: Chart simplification. Default `0.2`.
- `strokeWidth` [number]: Size of bars' stroke. Default: `1`.
- `title` [string]: Chart title. Optional.
- `titleFontSize` [string]: Font-size for chart title. Default: `'1rem'`.
- `tooltipFontSize` [string]: Font-size for tooltip. Default: `'0.95rem'`.


### `roughViz.Scatter`
Required
- `element` [string]: Id or class of container element.
- `data`: Data with which to construct chart.
  Can be either an object or string.

   - If object: must contain `x` and `y` keys:

    ```js
    new roughViz.Scatter({
       element: '.viz',
       data: {x: [1, 2, 35], y: [10, 20, 8]}
     })
    ```

   - If string: must be a path/url to a `csv` or `tsv`, and you must also specify the `x` and `y` as separate attributes that represent columns in said file:
   ```js
   new roughViz.Scatter({
     element: '#viz0',
     data: 'stringToDataUrl.csv',
     x: 'nameOfLabelsColumn',
     y: 'nameOfValuesColumn',
   })
   ```

Optional
- `axisFontSize` [string]: Font-size for axes' labels. Default: `'1rem'`.
- `axisRoughness` [number]: Roughness for x & y axes. Default: `0.5`.
- `axisStrokeWidth` [number]: Stroke-width for x & y axes. Default: `0.5`.
- `bowing` [number]: Chart bowing. Default: `0`.
- `colors` [array or string]: Array of colors for each arc. Default: `['coral', 'skyblue', '#66c2a5', 'tan', '#8da0cb', '#e78ac3', '#a6d854', '#ffd92f', 'tan', 'orange']`. If string (e.g. `'blue'`), all circles will take that color.
- `colorVar` [string]: If input data is `csv` or `tsv`, this should be an ordinal column with which to color points by.
`curbZero` [boolean]: Whether or not to force (x, y) axes to (0, 0). Default: `false`.
- `fillStyle` [string]: Bar fill-style. Should be one of [fillStyles](#fillStyle) shown above.
- `fillWeight` [number]: Weight of inner paths' color. Default: `0.5`.
- `font`: Font-family to use. You can use `0` or `gaegu` to use `Gaegu`, or `1` or `indie flower` to use `Indie Flower`. Or feed it something else. Default: `Gaegu`.
- `highlight` [string]: Color for each bar on hover. Default: `'coral'`.
- `highlightLabel` [string]: If input data is `csv` or `tsv`, this should be a column representing what value to display on hover. Otherwise, `(x, y)` values will be shown on hover.
- `innerStrokeWidth` [number]: Stroke-width for paths inside circles. Default: `1`.
- `interactive` [boolean]: Whether or not chart is interactive. Default: `true`.
- `labelFontSize` [string]: Font-size for axes' labels. Default: `'1rem'`.
- `margin` [object]: Margin object. Default: `{top: 50, right: 20, bottom: 70, left: 100}`
- `radius` [number]: Circle radius. Default: `8`.
- `roughness` [number]: Roughness level of chart. Default: `1`.
- `simplification` [number]: Chart simplification. Default `0.2`.
- `stroke` [string]: Color of circles' stroke. Default: `black`.
- `strokeWidth` [number]: Size of circles' stroke. Default: `1`.
- `title` [string]: Chart title. Optional.
- `titleFontSize` [string]: Font-size for chart title. Default: `'0.95rem'`.
- `tooltipFontSize` [string]: Font-size for tooltip. Default: `'0.95rem'`.
- `xLabel` [string]: Label for x-axis.
- `yLabel` [string]: Label for y-axis.


### `roughViz.StackedBar`
Required
- `element` [string]: Id or class of container element.
- `data`: Data with which to construct chart. Should be an object.
- `labels`: String name of label key in `data` object.

    ```js
    new roughViz.StackedBar({
       element: '#vis0',
       data: [
           {month:'Jan', A:20, B: 5},
           {month:'Feb', A:25, B: 10},
       ],
       labels: 'month',
     })
    ```

Optional
- `axisFontSize` [string]: Font-size for axes' labels. Default: `'1rem'`.
- `axisRoughness` [number]: Roughness for x & y axes. Default: `0.5`.
- `axisStrokeWidth` [number]: Stroke-width for x & y axes. Default: `0.5`.
- `bowing` [number]: Chart bowing. Default: `0`.
- `colors` [string]: Array of colors for each bar grouping.
- `fillStyle` [string]: Bar fill-style. Should be one of [fillStyles](#fillStyle) shown above.
- `fillWeight` [number]: Weight of inner paths' color. Default: `0.5`.
- `font`: Font-family to use. You can use `0` or `gaegu` to use `Gaegu`, or `1` or `indie flower` to use `Indie Flower`. Or feed it something else. Default: `Gaegu`.
- `highlight` [string]: Color for each bar on hover. Default: `'coral'`.
- `innerStrokeWidth` [number]: Stroke-width for paths inside bars. Default: `1`.
- `interactive` [boolean]: Whether or not chart is interactive. Default: `true`.
- `labelFontSize` [string]: Font-size for axes' labels. Default: `'1rem'`.
- `margin` [object]: Margin object. Default: `{top: 50, right: 20, bottom: 70, left: 100}`
- `padding` [number]: Padding between bars. Default: `0.1`.
- `roughness` [number]: Roughness level of chart. Default: `1`.
- `simplification` [number]: Chart simplification. Default `0.2`.
- `stroke` [string]: Color of bars' stroke. Default: `black`.
- `strokeWidth` [number]: Size of bars' stroke. Default: `1`.
- `title` [string]: Chart title. Optional.
- `titleFontSize` [string]: Font-size for chart title. Default: `'1rem'`.
- `tooltipFontSize` [string]: Font-size for tooltip. Default: `'0.95rem'`.
- `xLabel` [string]: Label for x-axis.
- `yLabel` [string]: Label for y-axis.



### Contributors
- [Jared Wilber](https://twitter.com/jdwlbr)
- [Laimonas Andriejauskas](https://github.com/laimonasA)
- [Dave Slutzkin](https://github.com/daveslutzkin)
- [JoLo](https://github.com/jolo-dev)
- [Lucas Wilber](https://github.com/lucasjwilber)

### Acknowledgements
This library wouldn't be possible without the following people:

- [Mike Bostock](https://twitter.com/mbostock) for [D3.js](https://d3js.org/).
- [Preet Shihn](https://twitter.com/preetster) for [rough.js](https://roughjs.com/).
- [Jo Wood](https://www.city.ac.uk/people/academics/jo-wood) for [handy](https://www.gicentre.net/software/#/handy/) processing lib.


### License
MIT License

Copyright (c) 2019 Jared Wilber

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
