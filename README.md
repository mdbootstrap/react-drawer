![MDB Logo](https://mdbootstrap.com/img/Marketing/general/logo/medium/mdb-react.png)

# MDB React 5

Responsive React navigation Drawer built with the latest Bootstrap 5. Examples like sliding side drawer in a container, multilevel, material, right drawer & more.

Check out [React Drawer Documentation](https://mdbootstrap.com/docs/react/extended/drawer) for detailed instructions & even more examples.

## Basic example 
![Drawer Basic Example](https://user-images.githubusercontent.com/108793661/184821773-96434d56-28b5-4bc8-a399-56413e83f261.png)
```js
import React, { useState } from 'react';
import {
  MDBSideNav,
  MDBSideNavMenu,
  MDBSideNavItem,
  MDBSideNavLink,
  MDBSideNavCollapse,
  MDBBtn,
  MDBIcon
} from 'mdb-react-ui-kit';

export default function App() {
  const [basicOpen, setBasicOpen] = useState(true);
  const [basicCollapse1, setBasicCollapse1] = useState(true);
  const [basicCollapse2, setBasicCollapse2] = useState(false);

  return (
    <>
      <MDBSideNav isOpen={basicOpen} absolute getOpenState={(e: any) => setBasicOpen(e)}>
        <MDBSideNavMenu>
          <MDBSideNavItem>
            <MDBSideNavLink>
              <MDBIcon far icon='smile' className='fa-fw me-3' />
              Link 1
            </MDBSideNavLink>
          </MDBSideNavItem>
          <MDBSideNavItem>
            <MDBSideNavLink icon='angle-down' shouldBeExpanded={basicCollapse1} onClick={() => setBasicCollapse1(!basicCollapse1)}>
              <MDBIcon fas icon='grin' className='fa-fw me-3' />
              Category 1
            </MDBSideNavLink>
            <MDBSideNavCollapse show={basicCollapse1}>
              <MDBSideNavLink>Link 2</MDBSideNavLink>
              <MDBSideNavLink>Link 3</MDBSideNavLink>
            </MDBSideNavCollapse>
          </MDBSideNavItem>
          <MDBSideNavItem>
            <MDBSideNavLink icon='angle-down' shouldBeExpanded={basicCollapse2} onClick={() => setBasicCollapse2(!basicCollapse2)}>
              <MDBIcon fas icon='grin' className='fa-fw me-3' />
              Category 2
            </MDBSideNavLink>
            <MDBSideNavCollapse show={basicCollapse2}>
              <MDBSideNavLink>Link 4</MDBSideNavLink>
              <MDBSideNavLink>Link 5</MDBSideNavLink>
            </MDBSideNavCollapse>
          </MDBSideNavItem>
        </MDBSideNavMenu>
      </MDBSideNav>

      <div style={{ padding: '20px' }} className='text-center'>
        <MDBBtn onClick={() => setBasicOpen(!basicOpen)}>
          <MDBIcon fas icon='bars' />
        </MDBBtn>
      </div>
    </>
  );
}
```

## How to use?

1. Download MDB 5 - PRO REACT UI KIT

2. Choose your favourite customized component and click on the image

3. Copy & paste the code into your MDB project

[▶️ Subscribe to YouTube channel for web development tutorials & resources](https://www.youtube.com/MDBootstrap?sub_confirmation=1)

## More examples (click on the image to see a live demo)
### Positioning:
[![React Drawer #1](https://user-images.githubusercontent.com/108793661/184822493-1e2f7ed4-b4f1-49fd-bb75-a3d908a38d39.png)](https://mdbootstrap.com/docs/react/extended/drawer#section-sidenav-positioning)

## Colors example:
[![React Drawer #2](https://user-images.githubusercontent.com/108793661/184822758-c15146b5-7ce1-40e4-b3e8-572e689109fe.png)](https://mdbootstrap.com/docs/react/extended/drawer#section-sidenav-colors)

## Dark example:
[![React Drawer #3](https://user-images.githubusercontent.com/108793661/184822933-cf96b292-a1ae-4216-b5a7-ce2a6cb1013e.png)](https://mdbootstrap.com/docs/react/extended/drawer#section-sidenav-dark)

## Inner scroll:
[![React Drawer #4](https://user-images.githubusercontent.com/108793661/184823092-a8ea2cd2-c388-40ad-9186-a7afc4837f85.png)](https://mdbootstrap.com/docs/react/extended/drawer#section-inner-scroll)

## Menu item scroll:
[![React Drawer #5](https://user-images.githubusercontent.com/108793661/184823259-d0e8b3da-4ff2-4b6d-aea2-a89ded73ea1c.png)](https://mdbootstrap.com/docs/react/extended/drawer#section-menu-item-scroll)

## Slim example:
[![React Drawer #6](https://user-images.githubusercontent.com/108793661/184823461-aaa80678-dffa-48a2-9ce4-49c916d8f717.png)](https://mdbootstrap.com/docs/react/extended/drawer#section-sidenav-slim)

You can find other examples [here](https://mdbootstrap.com/docs/react/extended/drawer).

<hr>

## More extended React documentation
<ul>
<li><a href="https://mdbootstrap.com/docs/react/extended/code/">React Bootstrap Code</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/gallery/">React Bootstrap Gallery</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/hamburger-menu/">React Bootstrap Hamburger Menu</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/jumbotron/">React Bootstrap Jumbotron</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/maps/">React Bootstrap Maps</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/mega-menu//">React Bootstrap Mega Menu</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/media-object/">React Bootstrap Media object</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/multiselect/">React Bootstrap Multiselect</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/masonry/">React Bootstrap Masonry</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/contact/">React Bootstrap Contact form</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/gradients/">React Bootstrap Gradients</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/pagination/">React Bootstrap Pagination</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/panels/">React Bootstrap Panels</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/social-media/">React Bootstrap Social Media icons & buttons</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/search/">React Bootstrap Search</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/table-sort/">React Bootstrap Table sort</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/table-responsive/">React Bootstrap Table responsive</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/table-scroll/">React Bootstrap Table scroll</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/table-search/">React Bootstrap Table search</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/textarea/">React Bootstrap Textarea</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/sidebar/">React Bootstrap Sidebar</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/profiles/">React Bootstrap Profiles</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/dropdown-multilevel/">React Bootstrap Nested Dropdown</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/bootstrap-address-form/">React Bootstrap Address Form</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/back-to-top">React Scroll Back to Top button</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/product-cards">React Product Cards</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/avatar">React Avatar</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/carousel-with-thumbnails">React Carousel Slider with Thumbnails</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/chat">React Chat</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/comparison-table">React Comparison table</a></li>
<li><a href="https://mdbootstrap.com/docs/react/extended/comments">React Comments</a></li>
</ul>
