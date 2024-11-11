# Teacher_Salary_Analysis
This repo is for an analysis of the average teacher salary in the united states compared with the cost of living index for each individual state. This is part of my quest to find out which state would you be better off having a career in teaching. Other variables, like average house price, may be added in the future.

## Data
- Cost of Living Data: [World Population Review Cost of Living Index](https://worldpopulationreview.com/state-rankings/cost-of-living-index-by-state)

- Teacher Salary Data: [World Population Review Teacher Pay](https://worldpopulationreview.com/state-rankings/teacher-pay-by-state)

## Visual Graph Analysis

For the Visual Graph Analysis, I normalized the average yearly income of teachers by state and the cost of living index in general and for different categories (groceries, health, housing, miscellaneous, transportation, utilities) and compared them.

<div>
  <button onclick="showImage('image1')">Normalized Annual Mean Salary (USD) vs Cost of Living Index by State</button>
  <button onclick="showImage('image2')">Image 2</button>
  <button onclick="showImage('image3')">Image 3</button>
  <button onclick="showImage('image4')">Image 4</button>
  <button onclick="showImage('image5')">Image 5</button>
  <button onclick="showImage('image6')">Image 6</button>
  <button onclick="showImage('image7')">Image 7</button>
</div>

<div id="imageContainer" style="margin-top: 20px;">
  <img id="image1" src="../Graphs/normalizedteacherpayvscostofliving.png" style="display: none; width: 100%; max-width: 500px;" />
  <img id="image2" src="path_to_image2.jpg" style="display: none; width: 100%; max-width: 500px;" />
  <img id="image3" src="path_to_image3.jpg" style="display: none; width: 100%; max-width: 500px;" />
  <img id="image4" src="path_to_image4.jpg" style="display: none; width: 100%; max-width: 500px;" />
  <img id="image5" src="path_to_image5.jpg" style="display: none; width: 100%; max-width: 500px;" />
  <img id="image6" src="path_to_image6.jpg" style="display: none; width: 100%; max-width: 500px;" />
  <img id="image7" src="path_to_image7.jpg" style="display: none; width: 100%; max-width: 500px;" />
</div>

<script>
  function showImage(id) {
    const images = document.querySelectorAll('#imageContainer img');
    images.forEach(img => img.style.display = 'none');
    document.getElementById(id).style.display = 'block';
  }
</script>