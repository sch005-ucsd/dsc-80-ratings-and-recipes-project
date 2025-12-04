# dsc-80-ratings-and-recipes-project

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Lab 06 — Practice with HTML Tags</title>
  <style>
    /* tiny, optional styling just to make it readable */
    img { max-width: 300px; height: auto; margin-right: 1rem; }
    .img-row { display: flex; gap: 1rem; flex-wrap: wrap; margin: 1rem 0; }
    table { border-collapse: collapse; margin-top: 1rem; }
    th, td { border: 1px solid #aaa; padding: .5rem .75rem; }
  </style>
</head>
<body>
  <!-- headers (need at least two) -->
  <h1>Lab 06: HTML Practice</h1>
  <h2>Images, Links, and Tables</h2>

  <p>This page contains images, links, and tables.</p>

  <h3>Images</h3>
  <div class="img-row">
    <figure>
      <img src="images/local_image.PNG" alt="Local Image" />
      <figcaption>Local image loaded from the project folder.</figcaption>
    </figure>

    <figure>
      <img src="https://cdn.ferrari.com/cms/network/media/img/resize/67af7411ef0bda001197c31c-ferrari-sf24-past-model-fullimg-d?width=1920&height=1080" alt="Ferrari SF-24" />
      <figcaption>Online image linked via URL.</figcaption>
    </figure>

    <figure>
      <img src="images/this-file-does-not-exist.png" alt="Default text shown if the image cannot be displayed" />
      <figcaption>Image demonstrating required default text via the <code>alt</code> attribute.</figcaption>
    </figure>
  </div>


  <h3>Links</h3>
  <ul>
    <li><a href="https://projectsekai.fandom.com/wiki/Momoi_Airi" target="_blank" rel="noopener">Momoi Airi</a></li>
    <li><a href="https://www.ferrari.com/en-EN/formula1/sf-24" target="_blank" rel="noopener">SF-24</a></li>
    <li><a href="http://en.wikipedia.org/wiki/Veterans_Day" target="_blank" rel="noopener">Veterans Day</a></li>
  </ul>


  <h3>Simple Table</h3>
  <table>
      <tr>
        <th>Luka Doncic</th>
        <th>Kyrie Irving</th>
      </tr>
      <tr>
        <td>77</td>
        <td>11</td>
      </tr>
  </table>

</body>