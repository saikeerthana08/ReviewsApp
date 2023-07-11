In this project, I build a **Reviews App**.

### Refer to the image below:

<br/>
<div style="text-align: center;">
<img src="https://assets.ccbp.in/frontend/content/react-js/reviews-app-output-v2.gif" alt="reviews app output" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

### Design Files

<details>
<summary>Click to view</summary>

- [Extra Small (Size < 576px), Small (Size >= 576px)](https://assets.ccbp.in/frontend/content/react-js/reviews-app-sm-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px)](https://assets.ccbp.in/frontend/content/react-js/reviews-app-lg-output.png)

</details>

### Completion Instructions

<details>
<summary>Functionalities added</summary>
<br/>

The app has the following functionalities

- When the left arrow is clicked, then the previous review details is displayed
- When the right arrow is clicked, then the next review details is displayed
- If the review that is being displayed is the first in the list of reviews
  - There will not be any state change when the left arrow is clicked
- If the review that is being displayed is the last in the list of reviews
  - There will not be any state change when the right arrow is clicked
- The `ReviewsCarousel` component receives the `reviewsList` as a prop. It consists of a list of review objects with the following properties in each review object

  |     Key     | Data Type |
  | :---------: | :-------: |
  |   imgUrl    |  String   |
  |  username   |  String   |
  | companyName |  String   |
  | description |  String   |

</details>

<details>
<summary>Implemented Files</summary>
<br/>

Used these files to complete the implementation:

- `src/components/ReviewsCarousel/index.js`
- `src/components/ReviewsCarousel/index.css`
</details>

### Resources

<details>
<summary>Image URLs</summary>

- [https://assets.ccbp.in/frontend/react-js/reviews-bg.png](https://assets.ccbp.in/frontend/react-js/reviews-bg.png)
- [https://assets.ccbp.in/frontend/react-js/left-arrow-img.png](https://assets.ccbp.in/frontend/react-js/left-arrow-img.png) alt should be **left arrow**
- [https://assets.ccbp.in/frontend/react-js/right-arrow-img.png](https://assets.ccbp.in/frontend/react-js/right-arrow-img.png) alt should be **right arrow**

</details>

<details>
<summary>Colors</summary>

<br/>

<div style="background-color: #ffffff ; width: 150px; padding: 10px; color: black">Hex: #ffffff</div>
<div style="background-color: #171f46 ; width: 150px; padding: 10px; color: white">Hex: #171f46</div>

</details>

<details>
<summary>Font-families</summary>

- Roboto

</details>
