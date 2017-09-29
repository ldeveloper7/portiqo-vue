<template>

    <div id="wrapper">
        <!-- start header -->

        <!-- Modal -->
        <div class="modal fade" id="myModal" role="dialog">
            <div class="modal-dialog">

                <!-- Modal content-->
                <div class="modal-content">
                    <div class="modal-header">
                        <button type="button" class="close" data-dismiss="modal">&times;</button>
                    </div>
                    <div class="modal-body">
                        <div class="row">
                            <div class="col-md-6 aligncenter">
                                <img src="img/pop-home.png" width="150">
                                <h6>Sign Up</h6>
                                <p class="light-small-text">Create a free Portiqo account<br>to get access to properties.</p>
                                <p class="signin">Already have an account? <a href="#">SIGN IN</a></p>
                            </div>
                            <div class="col-md-6">
                                <p class="pop-text">Enter your details</p>
                                <form name="signup" method="post" action="#" class="aligncenter">
                                    <input type="text" class="form-control input-field light-border" id="fname" placeholder="Full Name">
                                    <input type="text" class="form-control input-field light-border" id="email" placeholder="Email">
                                    <input type="text" class="form-control input-field light-border" id="mobile" placeholder="Mobile Number">
                                    <input type="text" class="form-control input-field light-border" id="address" placeholder="Property Address">
                                    <button type="button" class="btn btn-primary btn-block input-field peach-box">Create Account</button>
                                </form>
                            </div>
                        </div>
                    </div>
                    <div class="modal-footer">
                    </div>
                </div>

            </div>
        </div><!-- End Modal -->

        <header>
            <div class="navbar navbar-default fluid">
                <div class="container">
                    <div class="navbar-header">
                        <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
                            <span class="icon-bar"></span>
                            <span class="icon-bar"></span>
                            <span class="icon-bar"></span>
                        </button>
                        <a class="navbar-brand" href="index.html"><img src="img/logo.png" alt="Portiqo" /></a>
                    </div>
                    <div class="navbar-collapse collapse">
                        <ul class="nav navbar-nav" id="responsivemenu">
                            <li><a href="owner.html">owner</a></li>
                            <li><a href="agent.html">agent</a></li>
                            <li><a href="freelance.html">freelance</a></li>
                            <li><a href="referral.html">refer</a></li>
                            <li><a href="#">properties</a></li>
                            <li><a href="#" class="mgnr-15">login</a></li>
                            <li class="cont-btn"><a href="#" class="btn btn-small orange-btn" data-toggle="modal" data-target="#myModal">CONTACT</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </header>
        <!-- end header -->

        <div class="container mgnt-60">
            <p class="onboard_heading">Add Your Property</p>
        </div>

        <div class="container custom_container marb-40">
            <div id="sticky-anchor"></div>
            <div class="row bs-wizard" id="sticky">
                <div class="col-md-15 bs-wizard-step complete">
                    <div class="progress"><div class="progress-bar"></div></div>
                    <a href="property-type.html" class="bs-wizard-dot"></a>
                    <div class="text-center bs-wizard-stepnum marl-55">Property Type</div>
                </div>

                <div class="col-md-15 bs-wizard-step complete"><!-- complete -->
                    <div class="progress"><div class="progress-bar"></div></div>
                    <a href="add-photos.html" class="bs-wizard-dot"></a>
                    <div class="text-center bs-wizard-stepnum">Add Photos</div>
                </div>

                <div class="col-md-15 bs-wizard-step active"><!-- complete -->
                    <div class="progress"><div class="progress-bar"></div></div>
                    <a href="add-projects.html" class="bs-wizard-dot"></a>
                    <div class="text-center bs-wizard-stepnum">Add Project</div>
                </div>

                <div class="col-md-15 bs-wizard-step disabled"><!-- complete -->
                    <div class="progress"><div class="progress-bar"></div></div>
                    <a href="property-details.html" class="bs-wizard-dot"></a>
                    <div class="text-center bs-wizard-stepnum">Property Details</div>
                </div>

                <div class="col-md-15 bs-wizard-step disabled"><!-- active -->
                    <div class="progress"><div class="progress-bar"></div></div>
                    <a href="listing-details.html" class="bs-wizard-dot"></a>
                    <div class="text-center bs-wizard-stepnum marr-60">Listing Details</div>
                </div>
            </div>

        </div>

        <div class="container">
            <div class="row">
                <div class="col-md-12">
                    <div class="onboard_box">
                        <p class="onboard_box_heading-3 text-center">4 Projects Found</p>
                        <p class="onboard_heading_desc">
                            Freeway 21, Chepauk, Chennai
                        </p>
                        <div class="row mgnt-40">
                            <ul class="projects_found">
                                <li>
                                    <div class="pro_found_img">
                                        <img src="img/pro-found-1.jpg" alt="" />
                                    </div>
                                    <div class="pro_found_text">
                                        <span class="proj_name">Brigade Metropolis</span>
                                        <span class="proj_adrs">83 Laron Road Suite 058</span>
                                        <span class="proj_away">1.4 Km away</span>
                                    </div>
                                </li>
                                <li>
                                    <div class="pro_found_img">
                                        <img src="img/pro-found-2.jpg" alt="" />
                                    </div>
                                    <div class="pro_found_text">
                                        <span class="proj_name">West Angelo</span>
                                        <span class="proj_adrs">312 Deborah Meadow Apt. 918</span>
                                        <span class="proj_away">1.4 Km away</span>
                                    </div>
                                </li>
                                <li>
                                    <div class="pro_found_img">
                                        <img src="img/pro-found-3.jpg" alt="" />
                                    </div>
                                    <div class="pro_found_text">
                                        <span class="proj_name">New Carissa</span>
                                        <span class="proj_adrs">20 Ariel Circle Apt. 611</span>
                                        <span class="proj_away">1.4 Km away</span>
                                    </div>
                                </li>
                                <li>
                                    <div class="pro_found_img">
                                        <img src="img/pro-found-2.jpg" alt="" />
                                    </div>
                                    <div class="pro_found_text">
                                        <span class="proj_name">Port Kobe</span>
                                        <span class="proj_adrs">2029 Dietrich Via Suite 381</span>
                                        <span class="proj_away">1.4 Km away</span>
                                    </div>
                                </li>
                            </ul>
                        </div>
                        <p class="pro_font14 mart-50">Dont’ see your project?</p>
                        <p class="text-center marginbot50">
                            <a href="property-details.html" class="btn purple_btn mart-20"><i class="material-icons">location_on</i>add project</a>
                        </p>
                    </div>
                </div>
            </div>
        </div>

        <div class="container">
            <div class="row">
                <div class="col-md-12">
                    <div class="onboard_box postion_rel pad-10">
                        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d73963.42959917976!2d79.91876864091665!3d13.021407436275052!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3a5265ea4f7d3361%3A0x6e61a70b6863d433!2sChennai%2C+Tamil+Nadu!5e0!3m2!1sen!2sin!4v1505752460823" width="100%" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>
                        <div class="map_search_box">
                            <input class="location_search" type="textbox" name="" placeholder="Salarpuria Silverwoods">
                            <div class="checkbox_div">
                                <div class="checkbox">
                                    <input id="checkbox1" type="checkbox" checked>
                                    <label for="checkbox1">
                                        Show approximate location on listing
                                    </label>
                                </div>
                            </div>
                        </div>
                        <div class="location_pin"><img src="img/location-pin.png" alt="" /></div>
                    </div>
                </div>
            </div>
        </div>

    </div>


</template>