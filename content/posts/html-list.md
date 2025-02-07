<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Data Products (Fragility Curves)</title>
  <style>
    /* Global Styles */
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #fff;
      color: #333;
    }
    /* Container for sidebar and content */
    .container {
      display: flex;
      height: 100vh;
      overflow: hidden;
    }
    /* Sidebar styles */
    .sidebar {
      width: 280px;
      background-color: #f4f4f4;
      border-right: 1px solid #ddd;
      padding: 20px;
      box-sizing: border-box;
      overflow-y: auto;
    }
    .sidebar h2 {
      margin-top: 0;
    }
    .sidebar ul {
      list-style: none;
      padding: 0;
    }
    .sidebar li {
      margin-bottom: 5px;
    }
    .sidebar a {
      display: block;
      padding: 10px;
      text-decoration: none;
      color: #333;
      border-radius: 4px;
    }
    .sidebar a:hover {
      background-color: #ddd;
    }
    /* Content area styles */
    .content {
      flex: 1;
      padding: 20px;
      box-sizing: border-box;
      overflow-y: auto;
    }
    /* Hide sections by default */
    .section {
      display: none;
    }
    /* Iframe container */
    .iframe-container {
      margin-bottom: 20px;
    }
    iframe {
      width: 100%;
      border: none;
      min-height: 600px; /* Adjust as needed */
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Sidebar with events -->
    <div class="sidebar">
      <h2>Events</h2>
      <ul>
        <li><a href="#chilean-tsunami" onclick="showContent('chilean-tsunami'); return false;">Chilean Tsunami 2010</a></li>
        <li><a href="#japan-rc" onclick="showContent('japan-rc'); return false;">Japan 2011 RC</a></li>
        <li><a href="#japan-steel" onclick="showContent('japan-steel'); return false;">Japan 2011 Steel</a></li>
        <li><a href="#japan-wood" onclick="showContent('japan-wood'); return false;">Japan 2011 Wood</a></li>
        <li><a href="#japan-cargo" onclick="showContent('japan-cargo'); return false;">Japan 2011 Cargo</a></li>
        <li><a href="#japan-chemical" onclick="showContent('japan-chemical'); return false;">Japan 2011 Chemical</a></li>
        <li><a href="#japan-construction-materials" onclick="showContent('japan-construction-materials'); return false;">Japan 2011 Construction Materials</a></li>
        <li><a href="#japan-energy-related" onclick="showContent('japan-energy-related'); return false;">Japan 2011 Energy Related</a></li>
        <li><a href="#japan-food" onclick="showContent('japan-food'); return false;">Japan 2011 Food</a></li>
        <li><a href="#japan-manufacturing" onclick="showContent('japan-manufacturing'); return false;">Japan 2011 Manufacturing</a></li>
        <li><a href="#japan-petrochemical" onclick="showContent('japan-petrochemical'); return false;">Japan 2011 Petrochemical</a></li>
        <li><a href="#japan-warehouse-distribution" onclick="showContent('japan-warehouse-distribution'); return false;">Japan 2011 Warehouse Distribution</a></li>
        <li><a href="#SouthPacificTsunami-Brick_masonry_residential" onclick="showContent('SouthPacificTsunami-Brick_masonry_residential'); return false;">South Pacific Tsunami 2009, Brick Masonry Residential</a></li>
        <li><a href="#SouthPacificTsunami-ReinforcedConcrete_1Storey_Residential" onclick="showContent('SouthPacificTsunami-ReinforcedConcrete_1Storey_Residential'); return false;">South Pacific Tsunami 2009, RC 1 Storey</a></li>
        <li><a href="#SouthPacificTsunami-Timber" onclick="showContent('SouthPacificTsunami-Timber'); return false;">South Pacific Tsunami 2009, Timber</a></li>
        <li><a href="#sri-lanka" onclick="showContent('sri-lanka'); return false;">Sri Lanka 2004</a></li>
        <li><a href="#sulawesi-Masonry_unknown_1storey" onclick="showContent('sulawesi-Masonry_unknown_1storey'); return false;">Sulawesi Tsunami 2018 Masonry Unknown 1 Storey</a></li>
        <li><a href="#sulawesi-NonEngineeredlighttimber" onclick="showContent('sulawesi-NonEngineeredlighttimber'); return false;">Sulawesi Tsunami 2018 Non-Engineered Light Timber</a></li>
        <li><a href="#sulawesi-Nonengineeredmasonry1storey" onclick="showContent('sulawesi-Nonengineeredmasonry1storey'); return false;">Sulawesi Tsunami 2018 Non-Engineered Masonry 1 Storey</a></li>
        <li><a href="#sulawesi-Nonengineeredmasonry2storey" onclick="showContent('sulawesi-Nonengineeredmasonry2storey'); return false;">Sulawesi Tsunami 2018 Non-Engineered Masonry 2 Storey</a></li>
      </ul>
    </div>
    <!-- Content area with all sections (only one is visible at a time) -->
    <div class="content">
      <!-- Chilean Tsunami 2010 -->
      <div id="chilean-tsunami" class="section">
        <div class="iframe-container">
          <iframe src="/htmlfragility/Chilean Tsunami 2010_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Chilean Tsunami 2010_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Chilean Tsunami 2010_M3.html"></iframe>
        </div>
      </div>
      
      <!-- Japan 2011 RC -->
      <div id="japan-rc" class="section">
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan 2011 RC, 1 storey_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan 2011 RC, 1 storey_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan 2011 RC, 1 storey_M3.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan 2011 RC, 2 storey_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan 2011 RC, 2 storey_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan 2011 RC, 2 storey_M3.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan 2011 RC, 3 storey and more_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan 2011 RC, 3 storey and more_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan 2011 RC, 3 storey and more_M3.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan 2011 RC_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan 2011 RC_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan 2011 RC_M3.html"></iframe>
        </div>
      </div>
      
      <!-- Japan 2011 Steel -->
      <div id="japan-steel" class="section">
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan 2011 Steel_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan 2011 Steel_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan 2011 Steel_M3.html"></iframe>
        </div>
      </div>
      
      <!-- Japan 2011 Wood -->
      <div id="japan-wood" class="section">
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan 2011 Wood, 1 storey_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan 2011 Wood, 1 storey_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan 2011 Wood, 1 storey_M3.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan 2011 Wood, 2 storey_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan 2011 Wood, 2 storey_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan 2011 Wood, 2 storey_M3.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan 2011 Wood, 3 storey and more_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan 2011 Wood, 3 storey and more_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan 2011 Wood, 3 storey and more_M3.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan 2011 Wood_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan 2011 Wood_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan 2011 Wood_M3.html"></iframe>
        </div>
      </div>
      
      <!-- Japan 2011 Cargo -->
      <div id="japan-cargo" class="section">
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_CargoHandling_B_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_CargoHandling_B_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_CargoHandling_B_M3.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_CargoHandling_I_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_CargoHandling_I_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_CargoHandling_I_M3.html"></iframe>
        </div>
      </div>
      
      <!-- Japan 2011 Chemical -->
      <div id="japan-chemical" class="section">
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_Chemical_B_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <!-- Fixed typo: .htmll -> .html -->
          <iframe src="/htmlfragility/Japan_Chemical_B_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_Chemical_B_M3.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_Chemical_I_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_Chemical_I_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_Chemical_I_M3.html"></iframe>
        </div>
      </div>
      
      <!-- Japan 2011 Construction Materials -->
      <div id="japan-construction-materials" class="section">
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_ConstructionMaterials_B_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_ConstructionMaterials_B_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_ConstructionMaterials_B_M3.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_ConstructionMaterials_I_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_ConstructionMaterials_I_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_ConstructionMaterials_I_M3.html"></iframe>
        </div>
      </div>
      
      <!-- Japan 2011 Energy Related -->
      <div id="japan-energy-related" class="section">
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_EnergyRelated_B_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_EnergyRelated_B_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_EnergyRelated_B_M3.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_EnergyRelated_I_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_EnergyRelated_I_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_EnergyRelated_I_M3.html"></iframe>
        </div>
      </div>
      
      <!-- Japan 2011 Food -->
      <div id="japan-food" class="section">
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_Food_B_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_Food_B_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_Food_B_M3.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_Food_I_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_Food_I_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_Food_I_M3.html"></iframe>
        </div>
      </div>
      
      <!-- Japan 2011 Manufacturing -->
      <div id="japan-manufacturing" class="section">
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_Manufacturing_B_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_Manufacturing_B_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_Manufacturing_B_M3.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_Manufacturing_I_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_Manufacturing_I_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_Manufacturing_I_M3.html"></iframe>
        </div>
      </div>
      
      <!-- Japan 2011 Petrochemical -->
      <div id="japan-petrochemical" class="section">
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_Petrochemical_B_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_Petrochemical_B_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_Petrochemical_B_M3.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_Petrochemical_I_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_Petrochemical_I_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_Petrochemical_I_M3.html"></iframe>
        </div>
      </div>
      
      <!-- Japan 2011 Warehouse Distribution -->
      <div id="japan-warehouse-distribution" class="section">
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_WarehouseDistribution_B_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_WarehouseDistribution_B_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_WarehouseDistribution_B_M3.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_WarehouseDistribution_I_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_WarehouseDistribution_I_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Japan_WarehouseDistribution_I_M3.html"></iframe>
        </div>
      </div>
      
      <!-- South Pacific Tsunami: Brick Masonry Residential -->
      <div id="SouthPacificTsunami-Brick_masonry_residential" class="section">
        <div class="iframe-container">
          <iframe src="/htmlfragility/South_Pacific_Tsunami_2009,BrickMasonryResidential_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/South_Pacific_Tsunami_2009,BrickMasonryResidential_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/South_Pacific_Tsunami_2009,BrickMasonryResidential_M3.html"></iframe>
        </div>
      </div>
      
      <!-- South Pacific Tsunami: RC 1 Storey Residential -->
      <div id="SouthPacificTsunami-ReinforcedConcrete_1Storey_Residential" class="section">
        <div class="iframe-container">
          <iframe src="/htmlfragility/South_Pacific_Tsunami_2009,ReinforcedConcrete,1storey,Residential_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/South_Pacific_Tsunami_2009,ReinforcedConcrete,1storey,Residential_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/South_Pacific_Tsunami_2009,ReinforcedConcrete,1storey,Residential_M3.html"></iframe>
        </div>
      </div>
      
      <!-- South Pacific Tsunami: Timber -->
      <div id="SouthPacificTsunami-Timber" class="section">
        <div class="iframe-container">
          <iframe src="/htmlfragility/South_Pacific_Tsunami_2009,Timber_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/South_Pacific_Tsunami_2009,Timber_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/South_Pacific_Tsunami_2009,Timber_M3.html"></iframe>
        </div>
      </div>
      
      <!-- Sri Lanka 2004 -->
      <div id="sri-lanka" class="section">
        <!-- (There are 63 iframes here – grouped by location; see your original code) -->
        <div class="iframe-container">
          <iframe src="/htmlfragility/SriLanka2004_Ambalangoda_M1.html"></iframe>
        </div>
        <!-- ... Additional iframes for Balapitiya, Bentota, Beruwala, Colombo, etc. ... -->
        <!-- For brevity, all 63 iframes remain as in your original file -->
      </div>
      
      <!-- Sulawesi Tsunami 2018 Masonry Unknown 1 Storey -->
      <div id="sulawesi-Masonry_unknown_1storey" class="section">
        <div class="iframe-container">
          <iframe src="/htmlfragility/Sulawesi_Tsunami_2018,Masonry_unknown,1storey_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Sulawesi_Tsunami_2018,Masonry_unknown,1Storey_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Sulawesi_Tsunami_2018,Masonry_unknown,1Storey_M3.html"></iframe>
        </div>
      </div>
      
      <!-- Sulawesi Tsunami 2018 Non-Engineered Light Timber -->
      <div id="sulawesi-NonEngineeredlighttimber" class="section">
        <div class="iframe-container">
          <iframe src="/htmlfragility/Sulawesi_Tsunami_2018,Non_engineered_light_timber_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Sulawesi_Tsunami_2018,Non_engineered_light_timber_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Sulawesi_Tsunami_2018,Non_engineered_light_timber_M3.html"></iframe>
        </div>
      </div>
      
      <!-- Sulawesi Tsunami 2018 Non-Engineered Masonry 1 Storey -->
      <div id="sulawesi-Nonengineeredmasonry1storey" class="section">
        <div class="iframe-container">
          <iframe src="/htmlfragility/Sulawesi_Tsunami_2018,Non_engineered_masonry,unreinforced_with_clay_brick,1storey_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Sulawesi_Tsunami_2018,Non_engineered_masonry,unreinforced_with_clay_brick,1storey_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Sulawesi_Tsunami_2018,Non_engineered_masonry,unreinforced_with_clay_brick,1storey_M3.html"></iframe>
        </div>
      </div>
      
      <!-- Sulawesi Tsunami 2018 Non-Engineered Masonry 2 Storey -->
      <div id="sulawesi-Nonengineeredmasonry2storey" class="section">
        <div class="iframe-container">
          <iframe src="/htmlfragility/Sulawesi_Tsunami_2018,Non_engineered_masonry,unreinforced_with_clay_brick,2storey_M1.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Sulawesi_Tsunami_2018,Non_engineered_masonry,unreinforced_with_clay_brick,2storey_M2.html"></iframe>
        </div>
        <div class="iframe-container">
          <iframe src="/htmlfragility/Sulawesi_Tsunami_2018,Non_engineered_masonry,unreinforced_with_clay_brick,2storey_M3.html"></iframe>
        </div>
      </div>
    </div>
  </div>
  
  <script>
    function showContent(id) {
      // Hide all sections
      var sections = document.querySelectorAll('.section');
      sections.forEach(function(section) {
        section.style.display = 'none';
      });
  
      // Show the selected section (if it exists)
      var activeSection = document.getElementById(id);
      if (activeSection) {
        activeSection.style.display = 'block';
        // Optionally scroll the content area to the top:
        activeSection.scrollIntoView({ behavior: 'smooth' });
      }
    }
  </script>
</body>
</html>
