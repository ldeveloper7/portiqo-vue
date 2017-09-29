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

                <div class="col-md-15 bs-wizard-step complete"><!-- complete -->
                    <div class="progress"><div class="progress-bar"></div></div>
                    <a href="add-projects.html" class="bs-wizard-dot"></a>
                    <div class="text-center bs-wizard-stepnum">Add Project</div>
                </div>

                <div class="col-md-15 bs-wizard-step complete"><!-- complete -->
                    <div class="progress"><div class="progress-bar"></div></div>
                    <a href="property-details.html" class="bs-wizard-dot"></a>
                    <div class="text-center bs-wizard-stepnum">Property Details</div>
                </div>

                <div class="col-md-15 bs-wizard-step active"><!-- active -->
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
                        <div id="jssor_1" style="position:relative;margin:0 auto;top:0px;left:0px;width:980px;height:250px;overflow:hidden;visibility:hidden;">
                            <!-- Loading Screen -->
                            <div data-u="loading" class="jssorl-009-spin" style="position:absolute;top:0px;left:0px;width:100%;height:100%;text-align:center;background-color:rgba(0,0,0,0.7);">
                                <img style="margin-top:-19px;position:relative;top:50%;width:38px;height:38px;" src="img/spin.svg" />
                            </div>
                            <div data-u="slides" style="cursor:default;position:relative;top:0px;left:0px;width:980px;height:250px;overflow:hidden;">
                                <div>
                                    <img data-u="image" src="img/045.jpg" />
                                    <div u="thumb"><i class="material-icons md-24 md-white">collections</i>+12</div>
                                </div>
                                <div>
                                    <img data-u="image" src="img/043.jpg" />
                                    <div u="thumb"><i class="material-icons md-24 md-white">collections</i>+12</div>
                                </div>
                                <div>
                                    <img data-u="image" src="img/046.jpg" />
                                    <div u="thumb"><i class="material-icons md-24 md-white">collections</i>+12</div>
                                </div>
                                <div>
                                    <img data-u="image" src="img/047.jpg" />
                                    <div u="thumb"><i class="material-icons md-24 md-white">collections</i>+12</div>
                                </div>
                                <div>
                                    <img data-u="image" src="img/048.jpg" />
                                    <div u="thumb"><i class="material-icons md-24 md-white">collections</i>+12</div>
                                </div>
                                <div>
                                    <img data-u="image" src="img/044.jpg" />
                                    <div u="thumb"><i class="material-icons md-24 md-white">collections</i>+12</div>
                                </div>
                                <div>
                                    <img data-u="image" src="img/050.jpg" />
                                    <div u="thumb"><i class="material-icons md-24 md-white">collections</i>+12</div>
                                </div>
                                <div>
                                    <img data-u="image" src="img/049.jpg" />
                                    <div u="thumb"><i class="material-icons md-24 md-white">collections</i>+12</div>
                                </div>
                                <div>
                                    <img data-u="image" src="img/052.jpg" />
                                    <div u="thumb"></div>
                                </div>
                                <div>
                                    <img data-u="image" src="img/051.jpg" />
                                </div>
                                <a data-u="any" href="https://www.jssor.com" style="display:none">bootstrap slider</a>
                            </div>
                            <!-- Thumbnail Navigator -->
                            <div u="thumbnavigator" style="position:absolute;top:0px;right:0px;width:80px;height:50px;color:#FFF;overflow:hidden;cursor:default;background-color:rgba(0,0,0,.5);">
                                <div u="slides">
                                    <div u="prototype" style="position:absolute;top:0;left:0;width:80px;height:50px;">
                                        <div u="thumbnailtemplate" style="position:absolute;top:0;left:0;width:100%;height:100%;font-family:verdana;font-weight:normal;line-height:50px;font-size:14px;padding-left:10px;box-sizing:border-box;"></div>
                                    </div>
                                </div>
                            </div>
                            <!-- Arrow Navigator -->
                            <div data-u="arrowleft" class="jssora061" style="width:55px;height:55px;top:0px;left:25px;" data-autocenter="2" data-scale="0.75" data-scale-left="0.75">
                                <svg viewbox="0 0 16000 16000" style="position:absolute;top:0;left:0;width:100%;height:100%;">
                                    <path class="a" d="M11949,1919L5964.9,7771.7c-127.9,125.5-127.9,329.1,0,454.9L11949,14079"></path>
                                </svg>
                            </div>
                            <div data-u="arrowright" class="jssora061" style="width:55px;height:55px;top:0px;right:25px;" data-autocenter="2" data-scale="0.75" data-scale-right="0.75">
                                <svg viewbox="0 0 16000 16000" style="position:absolute;top:0;left:0;width:100%;height:100%;">
                                    <path class="a" d="M5869,1919l5984.1,5852.7c127.9,125.5,127.9,329.1,0,454.9L5869,14079"></path>
                                </svg>
                            </div>
                        </div>
                        <p class="slide_heading text-center">Salarpuria Silverwoods</p>
                        <p class="slide_sub_head">
                            1237 Vito Freeway Suite 224, Chepauk, Chennai
                        </p>
                    </div>
                </div>
            </div>

            <div class="row">
                <div class="col-md-12">
                    <div class="onboard_box">

                        <p class="onboard_box_heading-3 text-center">Listing Details</p>
                        <p class="onboard_heading_desc marb-40">
                            Add the final touches to your listing.
                        </p>
                        <div class="details_box mart-50">
                            <div class="details_box">
                                <div class="row spec_fields">
                                    <div class="col-md-6">
                                        <label>Monthly Rent</label>
                                        <input type="textbox" name="" class="form-control" placeholder=" &#x20B9; 25,000" />
                                    </div>
                                    <div class="col-md-6">
                                        <label>Lease Period</label>
                                        <input type="textbox" name="" class="form-control" placeholder="11" />
                                    </div>
                                    <div class="col-md-6">
                                        <label>Deposit</label>
                                        <input type="textbox" name="" class="form-control" placeholder=" &#x20B9; 2,50,000" />
                                    </div>
                                    <div class="col-md-6">
                                        <label>Date Available</label>
                                        <input type="textbox" name="" class="form-control" placeholder="11/12/2017" />
                                    </div>
                                    <div class="col-md-12">
                                        <label>Property Description</label>
                                        <textarea class="form-control" rows="3" placeholder="Located on the 13 Floor and is well planned with all modern amenities. The house has Vitrified flooring. It is vaastu compliant and faces North direction."></textarea>
                                    </div>
                                </div>
                            </div>

                            <div class="card border-card">
                                <div class="card-content">
                                    <div class="row bottom-border no-gutter">
                                        <div class="col-33 right-border"><a href="#" class="checked-value-left">Pets Allowed</a></div>
                                        <div class="col-33 right-border"><a href="#" class="check-value-left">Bachelors Allowed</a></div>
                                        <div class="col-33"><a href="#" class="check-value-left">Non Veg Allowed</a></div>
                                    </div>
                                </div>
                            </div>

                        </div>

                        <p class="text-center marginbot50">
                            <a href="listing-details-2.html" class="btn purple_btn">next</a>
                        </p>
                    </div>
                </div>
            </div>
        </div>

    </div>


</template>