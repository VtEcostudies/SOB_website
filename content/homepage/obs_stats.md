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


<style>
.activeTOOL {                                                        /* NEW */
        background: #eee;                                               /* NEW */
        box-shadow: 0 0 5px #999999;                                    /* NEW */
        color: #333;                                                    /* NEW */
        display: none;                                                  /* NEW */
        font-size: 12px;                                                /* NEW */                                                /* NEW */
        padding: 3px;                                                  /* NEW */
        position: relative;                                             /* NEW */
        text-align: center;                                             /* NEW */
        width: 80px;                                                    /* NEW */
        z-index: 10;                                                    /* NEW */
      }
</style>


<div class = "container" style = "background-color:#ffffff00">

<div class="row">
  <div class="col align-self-start">
    <div id="obsDoughnut" style = "font-size: 10pt"></div>
  </div>
  <div class="col align-self-end">
    <div id="speciesBreakdown" style = "font-size: 10pt"></div>
  </div>
</div> <!-- End of Row -->

</div> <!-- End of container -->
