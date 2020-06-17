# First App Part 2
<!-- - Create a repository -->
<!-- - Add More content -->
  <div>
    <a>
      About Us
    </a>
    <a>
      Service
    </a>
    <a>
      Something Else
    </a>
  </div>
  <!-- - Install Semantic UI -->
    - from this site: https://cdnjs.com/libraries/semantic-ui
    - <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/semantic-ui/2.4.1/semantic.min.css" integrity="sha256-9mbkOfVho3ZPXfM7W8sV2SndrGDuh7wuyLjtsWeTI1Q=" crossorigin="anonymous" />
  - Add More content
    - lorem ipsum: https://www.lipsum.com/feed/html
    - lorempicsum: https://picsum.photos/
  - Create other pages:
    - about us
    - Jobs
    - locations

- Add Glide Slider to a project https://glidejs.com/docs/setup/
  1- npm install @glidejs/glide
  2- Add to index.html <link rel="stylesheet" href="node_modules/@glidejs/glide/dist/css/glide.core.min.css">
  3- Add Slider
  <div class="glide">
    <div data-glide-el="track" class="glide__track">
      <ul class="glide__slides">
        <li class="glide__slide"></li>
        <li class="glide__slide"></li>
        <li class="glide__slide"></li>
      </ul>
    </div>
  </div>
  4- import Glide from '@glidejs/glide'

new Glide('.glide').mount()
