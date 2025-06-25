# my_gee_notes
// select a contry from FAO table ee.FeatureCollection("FAO/GAUL_SIMPLIFIED_500m/2015/level0")
var contry = contries.filter(ee.Filter.eq('ADM0_NAME', 'Germany'));
