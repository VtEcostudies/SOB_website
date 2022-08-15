---
title: "By the numbers"
weight: 5
---


<script src="js/jquery.min.js"></script>
<script src="js/tether.min.js"></script>
<script src="js/popper.min.js"></script>
<script src="js/bootstrap.min.js"></script>
<script src="js/jquery-ui.min.js"></script>
<script src="js/moment.min.js"></script>
<script src="https://d3js.org/d3.v4.js"></script>
<script src="https://d3js.org/d3-scale-chromatic.v1.min.js"></script>

<!-- load histogram plots -->
<!-- <script type='module' src="js/lineGraph.js"></script> -->
<!-- <script type='module' src="js/DoughnutGraph.js"></script> -->
<script type='module' src="js/count_tracker_static.js"></script>
<script type='module' src="js/number_obs_to_date_compare_previous.js"></script>
<script type='module' src="js/indentified_obs_to_date_compare_previous.js"></script>
<script type='module' src="js/iconic_taxa_tracker.js"></script>
<script type='module' src="js/taxon_breakdown.js"></script>
<script type='module' src="js/getFrequencyHistogram.js"></script>
<script type='module' src="js/species_tracker.js"></script>
<script type='module' src="js/observer_tracker.js"></script>

<!--<script type='module' src="js/iNat_api_calls.js"></script> -->
<!-- <script type="module" src="js/trial.js"></script> -->
<!-- Create a div where the graph will take place -->
<style>
.activeTOOL {                                                        /* NEW */
        background: #eee;                                               /* NEW */
        box-shadow: 0 0 5px #999999;                                    /* NEW */
        color: #333;                                                    /* NEW */
        display: none;                                                  /* NEW */
        font-size: 12px;                                                /* NEW */
        left: 130px;                                                    /* NEW */
        padding: 3px;                                                  /* NEW */
        position: absolute;                                             /* NEW */
        text-align: center;                                             /* NEW */
        top: 95px;                                                      /* NEW */
        width: 80px;                                                    /* NEW */
        z-index: 10;                                                    /* NEW */
      }
</style>

</head>
<body>
<h1 align="center">Vermont Atlas of Life Dashboard</h1>
<div class="opening">
<div class="container" style="background-color:#ffffff">
</div> <!-- End of 1st Row -->

<div class="row">
  <div class="col-xs-12 col-lg-6">
    <div id="obsDoughnut"></div>
  </div>
  <div class="col-xs-12 col-lg-6 static">
    <div id="speciesBreakdown"></div>
  </div>
</div> <!-- End of 2nd Row -->

<div class="row">
  <div id="observedSpecies"></div>
  <div id="observersVT"></div>
</div>

</div> <!-- End container -->
</div> <!-- End jumbotron -->
