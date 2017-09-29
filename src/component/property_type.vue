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
                <div class="col-md-15 bs-wizard-step active">
                    <div class="progress"><div class="progress-bar"></div></div>
                    <a href="property-type.html" class="bs-wizard-dot"></a>
                    <div class="text-center bs-wizard-stepnum marl-55">Property Type</div>
                </div>

                <div class="col-md-15 bs-wizard-step disabled"><!-- complete -->
                    <div class="progress"><div class="progress-bar"></div></div>
                    <a href="add-photos.html" class="bs-wizard-dot"></a>
                    <div class="text-center bs-wizard-stepnum">Add Photos</div>
                </div>

                <div class="col-md-15 bs-wizard-step disabled"><!-- complete -->
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
                        <p class="onboard_box_heading text-center">Select Property Type</p>
                        <div class="row">
                            <div class="col-md-1 col-sm-1"></div>

                            <div class="col-md-2 col-sm-2 porp_type">
                                <div class="porp_img">
                                    <img src="img/apartment.png" width="47px" alt="" />
                                </div>
                                <p>Apartment</p>
                            </div>

                            <div class="col-md-2 col-sm-2 porp_type">
                                <div class="porp_img">
                                    <img src="img/villa.png" width="102px" alt="" />
                                </div>
                                <p>Villa</p>
                            </div>

                            <div class="col-md-2 col-sm-2 porp_type">
                                <div class="porp_img">
                                    <img src="img/penthouse.png" width="51px" alt="" />
                                </div>
                                <p>Penthouse</p>
                            </div>

                            <div class="col-md-2 col-sm-2 porp_type">
                                <div class="porp_img">
                                    <img src="img/row-house.png" width="96px" alt="" />
                                </div>
                                <p>Row House</p>
                            </div>

                            <div class="col-md-2 col-sm-2 porp_type">
                                <div class="porp_img">
                                    <img src="img/Independent.png" width="63px" alt="" />
                                </div>
                                <p>Independent</p>
                            </div>

                            <div class="col-md-1 col-sm-1"></div>
                        </div>
                        <p class="text-center marginbot50">
                            <a href="property-type-selected.html" class="btn grey_btn">next</a>
                        </p>
                    </div>
                </div>
            </div>
        </div>

    </div>

</template>