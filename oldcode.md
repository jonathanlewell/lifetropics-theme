<!-- <nav class="site-navigation" role="navigation">

  <div class="wrapper flex--navigation">

    <div class="flex-column--menu">
      <a class="flex-button--navigation" href="#">
        <span class="flex-button--navigation__text">Browse</span>
        <svg class="button--navigation__svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="3" y1="12" x2="21" y2="12"></line><line x1="3" y1="6" x2="21" y2="6"></line><line x1="3" y1="18" x2="21" y2="18"></line></svg>
        <div class="flex-button--navigation__svg">Q</div>
      </a>
    </div>

    <div class="flex-column--search">
      <form action="/search" method="get" role="search" class="flex-form--search">

        <label for="Search" class="flex-form--search__default label-hidden">
          {{ 'general.search.placeholder' | t }}
        </label>

        <input class="flex-form--search__input" type="search"
           name="q"
           id="Search"
           value="{{ search.terms | escape }}"
           placeholder="{{ 'general.search.placeholder' | t }}">

        <button type="submit" class="flex-form--search__button">
        Q
        </button>
      </form>
    </div>

          <svg class="button--search__svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="11" cy="11" r="8"></circle><line x1="21" y1="21" x2="16.65" y2="16.65"></line></svg>

          <span class="icon-fallback-text">{{ 'general.search.submit' | t }}</span> 

    <div class="flex-column--cart">
      <a class="flex-button--cart" href="/cart">
        <div class="flex-button--cart__svg">Q</div>
        <div class="flex-button--cart__text">Cart</div>
        </a>
    </div>

        <svg class="button--cart__svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-shopping-cart"><circle cx="9" cy="21" r="1"></circle><circle cx="20" cy="21" r="1"></circle><path d="M1 1h4l2.68 13.39a2 2 0 0 0 2 1.61h9.72a2 2 0 0 0 2-1.61L23 6H6"></path></svg>

        <div class="hide-mobile">
          <span class="button--cart__text">
            {{ 'layout.cart.title' | t }}
            ({{ cart.item_count }}
            {{ 'layout.cart.items_count' | t: count: cart.item_count }})
          </span>
        </div>

  </div>
</nav>





<form action="/search" method="get" role="search" class="search-box">
       <label for="Search" class="label-hidden">
       </label>
       <div class="search-box__field">
        <input class="search-box__input" type="search"
             name="q"
             id="Search"
             value="e.g youremail@somewhere.com"
                 placeholder="e.g. jon@lifetropics.com" />
         <button type="submit" class="search-box__button button--newsletter">
            I want in
         </button>
        </div>
      </form>




      <div class="banner banner--home">

    <div class="wrapper">

        <div class="banner-layout">

            <div class="banner-copy">
                <h1 class="banner__headline banner__headline--light">
                Supplement Guides and Research to Improve Your Performance.</h1>
                <ul class="banner__list">
                <li class="banner__item banner__item--light">Hundreds of studies - with comments on their reliability </li>
                <li class="banner__item banner__item--light">Step-by-step guides with recommended dosages</li>
                <li class="banner__item banner__item--light">Stacking and alternative supplements to consider</li>
                </ul>
                <a class="button" href="https://lifetropics.com/blogs/posts">Browse Supplements →</a>
            </div>

            <div class="banner-media hide-mobile">
                <img class="banner-image" src="https://cdn.shopify.com/s/files/1/2803/5630/t/28/assets/jon.jpg?11686433428192613820" alt="Jon">
                <span class="banner-image__caption">If you need help, just ask me on live-chat. - Jon</span>
            </div>

        </div>
    </div>
</div>

-->