PLUGIN_VERSION=0.0.6
PLUGIN_ID=get-us-census-block

plugin:
	cat plugin.json|json_pp > /dev/null
	rm -rf dist
	mkdir dist
	zip --exclude "*.pyc" -r dist/dss-plugin-${PLUGIN_ID}-${PLUGIN_VERSION}.zip plugin.json custom-recipes
	
include ../Makefile.inc