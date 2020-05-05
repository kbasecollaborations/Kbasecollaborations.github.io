#How to start jbrowse?
<br>
cd LD/jbrowse-1.16.8-release
python3 -m RangeHTTPServer
#How to start ld server?
Use below code to run the linkage_server in parallel to see ld plots in jbrwose.
<br>
cd LD/jbrowse-1.16.8-release/plugins/MultiVariantViewer
node linkage_server/index.js
