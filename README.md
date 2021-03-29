# ATARI ONLINE


HOW-TO:

# 1. Add ATR images to the emulator.

See buildimg.sh.

Modify buildimg.sh adding the requited atr to be embedded in A8E.data file.

Modify the following lines on A8E.js based on the offset displayed by buildimg.sh script:

'''
// line 247 aprox.
new DataRequest(7310944, 7444080, 0, 0).open('GET', '/data/logospa.atr');
'''

'''
// line 387 aprox.
DataRequest.prototype.requests["/data/logospa.atr"].onload();
'''

