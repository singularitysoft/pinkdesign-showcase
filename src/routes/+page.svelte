<script>
  import "@appwrite.io/pink";
  import "@appwrite.io/pink-icons";
</script>

<div class="app">
  <h1>Sveltekit + Pinkdesign Showcase</h1>

  <div class="wrapper"> 
    <div class="card" style="border-radius: var(--border-radius-medium);"></div>
  </div>

  <div class="wrapper">
    <div class="card" style="box-shadow:var(--shadow-small);">
      <p class="text u-margin-block-start-8">shadow-small</p>
    </div>
    <div class="card" style="box-shadow:var(--shadow-large);">
      <p class="text u-margin-block-start-8">shadow-large</p>
    </div>    
  </div>
  
  <div class="wrapper">
    <h1 class="heading-level-1">Heading level 1</h1>
    <h2 class="heading-level-2">Heading level 2</h2>
    <h3 class="heading-level-3">Heading level 3</h3>
    <h4 class="heading-level-4">Heading level 4</h4>
    <h5 class="heading-level-5">Heading level 5</h5>
    <h6 class="heading-level-6">Heading level 6</h6>
    <h6 class="heading-level-7">Heading level 7</h6>
  </div>
  
  <div class="wrapper">
    <div class="icon-check u-color-text-disabled"></div>
    <div class="icon-check u-color-text-offline"></div>
    <div class="icon-check u-color-text-info"></div>
    <div class="icon-check u-color-text-danger"></div>
    <div class="icon-check u-color-text-warning"></div>
    <div class="icon-check u-color-text-success"></div>
    <div class="icon-check u-color-text-gray"></div>
    <div class="icon-check u-color-text-pink"></div>
  </div>
  
  <div class="wrapper">
    <div class="u-flex u-main-space-between u-min-width-100-percent card">
      <div class="box">1</div>
      <div class="box">2</div>
      <div class="box">3</div>
    </div>
  </div>
</div>

<div class="wrapper">
  <h4 class="eyebrow-heading-1">EYEBROW HEADING level 1</h4>
  <h5 class="eyebrow-heading-2">EYEBROW HEADING level 2</h5>
  <h6 class="eyebrow-heading-3">EYEBROW HEADING level 3</h6>
</div>

<div class="wrapper">
  <p class="u-bold">Body text level 1 SemiBold</p>
  <p>Body text level 1 Regular</p>
  <p class="u-bold">Body text level 2 SemiBold</p>
  <p>Body text level 2 Regular</p>
  <p style="text-decoration: underline">Body text level 2 Underline</p>
  <a class="link" href="/" alt="">Link text Underline</a>
</div>

<div class="wrapper">
  <input type="number" placeholder="without reset input" class="u-max-width-250" />
  <br />
  <input
    type="number"
    placeholder="with reset input"
    class="u-remove-input-number-buttons u-max-width-250"
  />
</div>

<div class="wrapper">
  <div>
    <p class="text u-x-small">x-small</p>
    <p class="text u-small">small</p>
    <p class="text">text</p>
    <p class="text u-bold">bold</p>
  </div>
</div>

<div class="wrapper">
  <div class="container">
    <p class="text u-margin-block-start-8">wrapper</p>
  </div>
</div>

<div class="wrapper">
  <ul
    class="grid-box"
    style="--grid-gap:1rem; --grid-item-size:16rem; --grid-item-size-small-screens:8rem;"
  >
    <li>
      <div class="card">card</div>
    </li>
    <li>
      <div class="card">card</div>
    </li>
    <li>
      <div class="card">card</div>
    </li>
    <li>
      <div class="card">card</div>
    </li>
    <li>
      <div class="card">card</div>
    </li>
    <li>
      <div class="card">card</div>
    </li>
  </ul>
</div>
  
  <div class="wrapper">
    <div class="side-nav">
      <div class="side-nav-main">
        <section class="drop-section">
          <ul class="drop-list">
            <li class="drop-list-item">
              <a class="drop-button is-selected" href="">
                <span class="icon-home" aria-hidden="true"></span>
                <span class="text">Menu item</span>
              </a>
            </li>
            <li class="drop-list-item">
              <a class="drop-button" href="">
                <span class="icon-user-group" aria-hidden="true"></span>
                <span class="text">Menu item</span>
              </a>
            </li>
            <li class="drop-list-item">
              <a class="drop-button" href="">
                <span class="icon-bell" aria-hidden="true"></span>
                <span class="text">Menu item</span>
              </a>
            </li>
            <li class="drop-list-item">
              <a class="drop-button" href="">
                <span class="icon-chart-pie" aria-hidden="true"></span>
                <span class="text">Menu item</span>
              </a>
            </li>
            <li class="drop-list-item">
              <a class="drop-button" href="">
                <span class="icon-document" aria-hidden="true"></span>
                <span class="text">Menu item</span>
              </a>
            </li>
          </ul>
        </section>
      </div>
      <div class="side-nav-bottom">
        <section class="drop-section">
          <a class="drop-button" href="">
            <span class="icon-cog" aria-hidden="true"></span>
            <span class="text">Menu item</span>
          </a>
        </section>
      </div>
    </div>
    
  </div>
  
  <div class="wrapper">
    <nav class="pagination">
      <span href="" class="button is-text is-disabled" aria-label="prev page">
        <span class="icon-cheveron-left" aria-hidden="true"></span>
        <span class="text">Prev</span>
      </span>
      <ol class="pagination-list is-only-desktop">
        <li class="pagination-item">
          <span href="" class="button is-disabled" aria-label="page"><span class="text">1</span></span>
        </li>
        <li class="pagination-item">
          <button class="button is-text /*u-hide*/" aria-label="show prev 5 pages">
            <span class="icon">…</span>
          </button>
        </li>
        <li class="pagination-item">
          <button class="button is-text" aria-label="page"><span class="text">2</span></button>
        </li>
        <li class="pagination-item">
          <button class="button is-text" aria-label="page"><span class="text">3</span></button>
        </li>
        <li class="pagination-item">
          <button class="button is-text" aria-label="page"><span class="text">4</span></button>
        </li>
        <li class="pagination-item">
          <button class="button is-text" aria-label="page"><span class="text">5</span></button>
        </li>
        <li class="pagination-item">
          <button class="button is-text" aria-label="show next 5 pages">
            <span class="icon">…</span>
          </button>
        </li>
        <li class="pagination-item">
          <button class="button is-text" aria-label="page"><span class="text">20</span></button>
        </li>
      </ol>
      <a href="" class="button is-text" aria-label="next page">
        <span class="text">Next</span>
        <span class="icon-cheveron-right" aria-hidden="true"></span>
      </a>
    </nav>    
  </div>

<div class="wrapper">
  <div class="boxes-wrapper">
    <div class="box u-flex u-gap-16 u-cross-center">Top Box</div>
    <div class="box u-flex u-gap-16 u-cross-center">Middle Box</div>
    <div class="box u-flex u-gap-16 u-cross-center">Middle Box</div>
    <div class="box u-flex u-gap-16 u-cross-center">Bottom Box</div>
  </div>  
</div>

<div class="wrapper">
  <button class="button"><span class="text">Primary</span></button>
<button class="button is-secondary"><span class="text">Secondary</span></button>
<button class="button is-text"><span class="text">Text</span></button>
<button class="button is-only-icon" aria-label="Add new item">
  <span class="icon-plus" aria-hidden="true"></span>
</button>
<button class="button is-text is-only-icon" style="--button-size:2.5rem;" aria-label="Remove item">
  <span class="icon-x" aria-hidden="true"></span>
</button>
</div>

<div class="wrapper">
  <button class="button"><span class="text">Medium</span></button>
<button class="button is-big"><span class="text">Large</span></button>
</div>
  
<div class="wrapper">
  <button class="button is-secondary" aria-label="Add new item">
    <span class="icon-plus" aria-hidden="true"></span>
    <span class="text">Button</span>
  </button>
  <button class="button is-secondary" aria-label="Add new item">
    <span class="icon-cheveron-left" aria-hidden="true"></span>
    <span class="text">Button</span>
  </button>
  <button class="button is-secondary" aria-label="Add new item">
    <span class="text">Button</span>
    <span class="icon-cheveron-right" aria-hidden="true"></span>
  </button>
  <button class="button is-secondary" aria-label="Add new item">
    <span class="icon-trash" aria-hidden="true"></span>
    <span class="text">Button</span>
  </button>
  <button class="button is-secondary" aria-label="Add new item">
    <span class="icon-duplicate" aria-hidden="true"></span>
    <span class="text">Button</span>
  </button>
  <button class="button is-secondary" aria-label="Add new item">
    <span class="icon-download" aria-hidden="true"></span>
    <span class="text">Button</span>
  </button>
  <button class="button is-secondary" aria-label="Add new item">
    <span class="icon-external-link" aria-hidden="true"></span>
    <span class="text">Button</span>
  </button>
  
</div>

<div class="wrapper">
  <ul class="buttons-list u-margin-auto">
    <li class="buttons-list-item">
      <button class="button is-text"><span class="text">Button 1</span></button>
    </li>
    <li class="buttons-list-item">
      <button class="button is-text"><span class="text">Button 2</span></button>
    </li>
    <li class="buttons-list-item">
      <button class="button is-text"><span class="text">Button 3</span></button>
    </li>
    <li class="buttons-list-item">
      <button class="button is-text"><span class="text">Button 4</span></button>
    </li>
  </ul>
  
</div>

<div class="wrapper">
  <input type="checkbox" />
<input type="checkbox" checked="true" />

</div>

<div class="wrapper">
  <input type="checkbox" disabled />
<input type="checkbox" checked="true" disabled />

</div>

<div class="wrapper">
  <input type="checkbox" class="is-small" />
<input type="checkbox" checked="true" />
<input type="checkbox" class="is-large" />

</div>

<div class="wrapper">
  <form class="form u-width-full-line u-max-width-500">
    <ul class="form-list">
      <li class="form-item">
        <label class="label">Label</label>
        <div class="input-text-wrapper">
          <input type="text" class="input-text" placeholder="Placeholder" />
        </div>
      </li>
    </ul>
  </form>
  
</div>

<div class="wrapper">
  <div class="input-text-wrapper is-with-end-button u-width-full-line u-max-width-500">
    <input type="search" placeholder="Search" />
    <div class="icon-search" aria-hidden="true"></div>
    <button
      class="button is-text is-only-icon"
      aria-label="Clear search"
      style="--button-size:1.5rem;"
    >
      <span class="icon-x" aria-hidden="true"></span>
    </button>
  </div>
  
</div>

<div class="wrapper">
  <div class="input-text-wrapper is-with-end-button u-width-full-line u-max-width-500">
    <input type="search" placeholder="Search" />
    <div class="icon-search" aria-hidden="true"></div>
    <button
      class="button is-text is-only-icon"
      aria-label="Clear search"
      style="--button-size:1.5rem;"
    >
      <span class="icon-x" aria-hidden="true"></span>
    </button>
  </div>
  
</div>

<div class="wrapper">
  <form class="form u-width-full-line u-max-width-500">
    <ul class="form-list">
      <li class="form-item">
        <label class="label">Label</label>
        <div class="input-text-wrapper">
          <input type="password" class="input-text" placeholder="Placeholder" />
          <button class="show-password-button" aria-label="show password">
            <span class="icon-eye" aria-hidden="true"></span>
          </button>
        </div>
      </li>
      <li class="form-item">
        <label class="label">Label</label>
        <div class="input-text-wrapper" style="--amount-of-buttons:2">
          <input type="text" placeholder="Placeholder" />
          <div class="options-list">
            <button class="options-list-button" aria-label="show password / hide password">
              <span class="icon-eye" aria-hidden="true"></span>
            </button>
            <button class="options-list-button" aria-label="copy text">
              <span class="icon-duplicate" aria-hidden="true"></span>
            </button>
          </div>
        </div>
      </li>
    </ul>
  </form>
  
</div>

<div class="wrapper">
  <form class="form u-width-full-line u-max-width-500">
    <ul class="form-list">
      <li class="form-item">
        <label class="label">Label</label>
        <input type="file" name="file" id="file-file" size="1" />
      </li>
    </ul>
  </form>
  
</div>

<div class="wrapper">
  <form class="form u-width-full-line u-max-width-500">
    <ul class="form-list">
      <li class="form-item">
        <label class="label">Label</label>
        <div class="tags-input">
          <div class="tags">
            <ul class="tags-list">
              <li class="tags-item">
                <div class="input-tag">
                  <span class="tag-text">
                    role
                    <div></div>
                  </span>
                  <button class="input-tag-delete-button" aria-label="delete all:role tag">
                    <span class="icon-x" aria-hidden="true"></span>
                  </button>
                </div>
              </li>
            </ul>
          </div>
          <input type="text" class="tags-input-text" placeholder="Placeholder" />
        </div>
      </li>
    </ul>
  </form>
  
</div>

<div class="wrapper">
  <form class="form u-width-full-line u-max-width-500">
    <ul class="form-list">
      <li class="form-item">
        <label class="label">Label</label>
        <div class="select u-width-full-line">
          <select name="pets" id="pet-select">
            <option value="">Select option</option>
            <option value="1">Option 1</option>
            <option value="2">Option 2</option>
            <option value="3">Option 3</option>
            <option value="4">Option 4</option>
            <option value="5">Option 5</option>
            <option value="6">Option 6</option>
          </select>
          <span class="icon-cheveron-down" aria-hidden="true"></span>
        </div>
      </li>
    </ul>
  </form>
  
</div>

<div class="wrapper">
  <form class="form u-width-full-line u-max-width-500">
    <ul class="form-list">
      <li class="form-item">
        <label class="label">Label</label>
        <textarea class="input-text" placeholder="Type here..."></textarea>
      </li>
    </ul>
  </form>
  
</div>

<div class="wrapper">
  <form class="form u-width-full-line u-max-width-500">
    <ul class="form-list">
      <li class="form-item">
        <label class="label">Label</label>
        <input type="text" class="input-text" value="placeholder text" />
      </li>
      <li class="form-item">
        <label class="label">Label</label>
        <input type="text" class="input-text" value="placeholder text" disabled />
      </li>
      <li class="form-item">
        <label class="label">Label</label>
        <input type="text" class="input-text" value="placeholder text" readonly />
      </li>
    </ul>
  </form>
</div>

<div class="wrapper">
  <p class="text u-margin-block-start-8">
    To open search box please press
    <kbd class="kbd">⌘</kbd>
    +
    <kbd class="kbd">K</kbd>
    buttons.
  </p>  
</div>

<style>
  h1 {
    font-size: 20px;
  }

  .app {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100vh;
  }

  .icon-check {
    text-align: center;
  }
</style>