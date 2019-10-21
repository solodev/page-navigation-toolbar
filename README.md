# page-navigation-toolbar
You may find that you have too much page content to ideally fit a single page. Rather than creating a series of child pages, however, you can include a Page Navigation Toolbar that allows you to tab between content on a single page.

## Tutorial		  
For detailed instruction's, view Solodev's [How to Integrate Tabs into your Page Content with a Page Navigation Toolbar](https://www.solodev.com/blog/web-design/how-to-integrate-tabs-into-your-page-content-with-a-page-navigation-toolbar.stml) article.
 
## Demo  		  
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/6nugkjre/1/).

## HTML
The tutorial contains the following basic HTML markup.

```
 <div class="border-bottom py-3">
                <div class="container">
                  <div class="row align-items-center justify-content-between">
                    <div class="col-md-9 col-lg-10">
                      <ul class="nav nav-underline border-0 justify-content-between justify-content-md-start">
                        <li class="nav-item mr-md-4"><a data-toggle="tab" class="text-graphite active" href="#locations" aria-selected="true">Locations</a>
                        </li>
                        <li class="nav-item mr-md-4"><a data-toggle="tab" class="text-graphite" href="#explore" aria-selected="false">Explore</a>
                        </li>
                        <li class="nav-item mr-md-4"><a data-toggle="tab" class="text-graphite" href="#mission" aria-selected="false">Mission</a>
                        </li>
                      </ul>
                    </div>
                  </div>
                </div><!-- container -->
              </div>
              <div class="container">
                <div class="tab-content mt-md-6 mt-4">
                  <div id="locations" class="tab-pane show active" role="tabpanel">
                        <h2 class="text-center p-3">Locations</h2>
                    <div class="row align-items-center">
                      <div class="col-md-8 mx-auto text-md-center">
                        <p class="mb-4">The dream of colonizing the moon, Mars, and beyond requires space travel and long-term habitation. LunarXP has pioneered new technologies and environments that make space flight and colony living not just safe – but unexpectedly comfortable. From our surface stations to our orbital platform, learn more about the different colonial posts in the LunarXP community.</p>
                      </div>
                    </div>
                    <div class="row mt-6">
                      <div class="col-md-12">
                        <div class="row text-center">
                          <div class="col-md-4 px-3">
                            <img alt="XP-1" class="img-fluid border" src="images/xp-1.jpg">
                            <h3 class="text-orange mt-4">XP-1</h3>
                            <p class="mt-4">Live and work in the first sustainable settlement on another planet.</p>
                          </div>
                          <div class="col-md-4 px-3">
                            <img alt="HAB-1" class="img-fluid border" src="images/hab-1.jpg">
                            <h3 class="text-orange mt-4">HAB-1</h3>
                            <p class="mt-4">Tour your “home away from home” on the surface of the moon.</p>
                          </div>
                          <div class="col-md-4 px-3">
                            <img alt="Orbiter-1" class="img-fluid border" src="images/orbiter-1.jpg">
                            <h3 class="text-orange mt-4">Orbiter-1</h3>
                            <p class="mt-4">Be part of the crew on the most advanced space station ever built.</p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div id="explore" class="tab-pane fade text-center" role="tabpanel">
                        <h2 class="p-3">Explore</h2>
                        <div class="container py-2 text-left">
                                <div class="row py-3">
                                    <div class="col-md-5">
                                        <h1 class="h3">Watch Our Latest Video, "From the Moon to Mars"</h1>
                                        <p class="my-4">Since the dawn of time, mankind has looked to the stars with restless hearts and endless wonder. Not since the Apollo moon program have we endeavored to travel so far from Earth - and LunarXP is where it begins.
                                        </p><p><strong>Are you ready to explore?</strong></p>
                                        <a href="#" class="mt-3 btn btn-secondary text-white">Watch the Video</a>
                                    </div>
                                    <div class="col-md-6 ml-auto mt-md-0 mt-5">
                                        <img class="w-100 img-fluid" alt="Lunar XP Video" src="images/explore.jpg">
                                    </div>
                                </div>
                            </div>
                  </div>
                  <div id="mission" class="tab-pane fade text-center" role="tabpanel">
                      <h2 class="p-3">Mission</h2>
                    <p>At LunarXP, we’re dreamers and explorers. 
                    We’ve always looked up for purpose – and we’ve never looked back. 
                    As a company, we believe that the future of mankind lies beyond earth and in the stars. 
                    Together, we can make a better tomorrow for all of us. It starts with one small step.</p>
                  </div>
                </div><!-- tab content -->
</div><!-- container -->  
```

## External Resources
This tutorial includes the following third party resources.

```
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
<!-- jQuery first, then Popper.js, then Bootstrap JS -->
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
```
