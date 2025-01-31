<div id="content-box"></div>

<script>
const fileMapping = {
  "Brick masonry residential_South Pacific Tsunami 2009": ["M1", "M2", "M3"],
  "Chilean Tsunami 2010": ["M1", "M2", "M3"],
  "Japan 2011 RC, 1 storey": ["M1", "M2", "M3"],
  "Japan 2011 RC, 2 storey": ["M1", "M2", "M3"],
  "Japan 2011 RC, 3 storey and more": ["M1", "M2", "M3"],
  "Japan 2011 RC": ["M1", "M2", "M3"], // Added
  "Japan 2011 Steel": ["M1", "M2", "M3"],
  "Japan 2011 Wood": ["M1", "M2", "M3"], // Added
  "Japan 2011_Wood, 1 storey": ["M1", "M2", "M3"], // Added
  "Japan 2011_Wood, 2 storey": ["M1", "M2", "M3"], // Added
  "Japan 2011_Wood, 3 storey and more": ["M1", "M2", "M3"], // Added
  "Japan_CargoHandling_B": ["M1", "M2", "M3"], // Added
  "Japan_CargoHandling_I": ["M1", "M2", "M3"], // Added
  "Japan_Chemical_B": ["M1", "M2", "M3"], // Added
  "Japan_Chemical_I": ["M1", "M2", "M3"], // Added
  "Japan_ConstructionMaterials_B": ["M1", "M2", "M3"], // Added
  "Japan_ConstructionMaterials_I": ["M1", "M2", "M3"], // Added
  "Japan_EnergyRelated_B": ["M1", "M2", "M3"], // Added
  "Japan_EnergyRelated_I": ["M1", "M2", "M3"], // Added
  "Japan_Food_B": ["M1", "M2", "M3"], // Added
  "Japan_Food_I": ["M1", "M2", "M3"], // Added
  "Japan_Manufacturing_B": ["M1", "M2", "M3"], // Added
  "Japan_Manufacturing_I": ["M1", "M2", "M3"], // Added
  "Japan_Petrochemical_B": ["M1", "M2", "M3"], // Added
  "Japan_Petrochemical_I": ["M1", "M2", "M3"], // Added
  "Japan_WarehouseDistribution_B": ["M1", "M2", "M3"], // Added
  "Japan_WarehouseDistribution_I": ["M1", "M2", "M3"], // Added
  "Masonry, unknown, 1 storey_Sulawesi Tsunami 2018": ["M1", "M2", "M3"],
  "Non engineered light timber_Sulawesi Tsunami 2018": ["M1", "M2", "M3"],
  "Non engineered masonry, un reinforced with clay brick, 1 storey_Sulawesi Tsunami 2018": ["M1", "M2", "M3"],
  "Non engineered masonry, un reinforced with clay brick, 2 storey_Sulawesi Tsunami 2018": ["M1", "M2", "M3"],
  "Reinforced Concrete, 1 storey, residential_South Pacific Tsunami 2009": ["M1", "M2", "M3"],
  "SriLanka2004_Ambalangoda": ["M1", "M2", "M3"],
  "SriLanka2004_Balapitiya": ["M1", "M2", "M3"],
  "SriLanka2004_Bentota": ["M1", "M2", "M3"],
  "SriLanka2004_Beruwala": ["M1", "M2", "M3"],
  "SriLanka2004_Colombo": ["M1", "M2", "M3"],
  "SriLanka2004_Dehiwala": ["M1", "M2", "M3"],
  "SriLanka2004_Devinuwara": ["M1", "M2", "M3"],
  "SriLanka2004_Dickwella": ["M1", "M2", "M3"],
  "SriLanka2004_Galle4Gravets": ["M1", "M2", "M3"],
  "SriLanka2004_Habaraduwa": ["M1", "M2", "M3"],
  "SriLanka2004_Hikkaduwa": ["M1", "M2", "M3"],
  "SriLanka2004_Kalutara": ["M1", "M2", "M3"],
  "SriLanka2004_Matara4Gravets": ["M1", "M2", "M3"],
  "SriLanka2004_Moratuwa": ["M1", "M2", "M3"],
  "SriLanka2004_Negombo": ["M1", "M2", "M3"],
  "SriLanka2004_Panadura": ["M1", "M2", "M3"],
  "SriLanka2004_Rathmalana": ["M1", "M2", "M3"],
  "SriLanka2004_Thimbirigasyaya": ["M1", "M2", "M3"],
  "SriLanka2004_TotalArea": ["M1", "M2", "M3"],
  "SriLanka2004_Wattala": ["M1", "M2", "M3"],
  "SriLanka2004_Weligama": ["M1", "M2", "M3"],
  "Timber_South Pacific Tsunami 2009": ["M1", "M2", "M3"],
};

function showContent(baseName, mValue) {
  const fileName = `/htmlfragility/${baseName}_${mValue}.html`;
  document.getElementById("content-box").innerHTML = `<iframe src="${fileName}" width="100%" height="800px"></iframe>`;
}

// Example usage:
// showContent("Brick masonry residential_South Pacific Tsunami 2009", "M2");

// To populate a dropdown or list:
let optionsHtml = "";
for (const baseName in fileMapping) {
  optionsHtml += `<optgroup label="${baseName}">`;
  for (const mValue of fileMapping[baseName]) {
    optionsHtml += `<option value="${baseName},${mValue}">${baseName} - ${mValue}</option>`;
  }
  optionsHtml += `</optgroup>`;
}

const selectElement = document.createElement('select');
selectElement.innerHTML = optionsHtml;
selectElement.addEventListener('change', function() {
    const [baseName, mValue] = this.value.split(',');
    showContent(baseName, mValue);
});

document.body.insertBefore(selectElement, document.getElementById("content-box")); // Insert before the content box
</script>