WebP Express 0.15.3. Conversion triggered using bulk conversion, 2019-09-24 07:56:21

*WebP Convert 2.1.4*  ignited.
- PHP version: 7.3.1
- Server software: Apache

Stack converter ignited

Options:
------------
The following options have been set explicitly. Note: it is the resulting options after merging down the "jpeg" and "png" options and any converter-prefixed options.
- source: [doc-root]/wp-content/uploads/2017/02/spicy-sardine-open-sandwich-568x379.jpg
- destination: [doc-root]/wp-content/webp-express/webp-images/doc-root/wp-content/uploads/2017/02/spicy-sardine-open-sandwich-568x379.jpg.webp
- log-call-arguments: true
- converters: (array of 9 items)

The following options have not been explicitly set, so using the following defaults:
- converter-options: (empty array)
- shuffle: false
- preferred-converters: (empty array)
- extra-converters: (empty array)

The following options were supplied and are passed on to the converters in the stack:
- default-quality: 70
- encoding: "auto"
- max-quality: 80
- metadata: "none"
- near-lossless: 60
- quality: "auto"
------------


*Trying: cwebp* 

Options:
------------
The following options have been set explicitly. Note: it is the resulting options after merging down the "jpeg" and "png" options and any converter-prefixed options.
- source: [doc-root]/wp-content/uploads/2017/02/spicy-sardine-open-sandwich-568x379.jpg
- destination: [doc-root]/wp-content/webp-express/webp-images/doc-root/wp-content/uploads/2017/02/spicy-sardine-open-sandwich-568x379.jpg.webp
- default-quality: 70
- encoding: "auto"
- low-memory: true
- log-call-arguments: true
- max-quality: 80
- metadata: "none"
- method: 6
- near-lossless: 60
- quality: "auto"
- use-nice: true
- command-line-options: ""
- try-common-system-paths: true
- try-supplied-binary-for-os: true

The following options have not been explicitly set, so using the following defaults:
- alpha-quality: 85
- auto-filter: false
- preset: "none"
- size-in-percentage: null (not set)
- skip: false
- rel-path-to-precompiled-binaries: *****
------------

Encoding is set to auto - converting to both lossless and lossy and selecting the smallest file

Converting to lossy
Locating cwebp binaries
1 cwebp binaries found in common system locations
Checking if we have a supplied binary for OS: Darwin... We do.
We in fact have 1
A total of 2 cwebp binaries where found
Detecting versions of the cwebp binaries found (and verifying that they can be executed in the process)
Executing: /usr/local/bin/cwebp -version. Result: version: 1.0.3
Executing: [doc-root]/wp-content/plugins/webp-express/vendor/rosell-dk/webp-convert/src/Convert/Converters/Binaries/cwebp-mac12 -version
Exec failed (the cwebp binary was not found at path: [doc-root]/wp-content/plugins/webp-express/vendor/rosell-dk/webp-convert/src/Convert/Converters/Binaries/cwebp-mac12)
Trying executing the cwebs found until success. Starting with the ones with highest version number.
Creating command line options for version: 1.0.3
Quality of source is 90. This is higher than max-quality, so using max-quality instead (80)
The near-lossless option ignored for lossy
Trying to convert by executing the following command:
nice /usr/local/bin/cwebp -metadata none -q 80 -alpha_q '85' -m 6 -low_memory '[doc-root]/wp-content/uploads/2017/02/spicy-sardine-open-sandwich-568x379.jpg' -o '[doc-root]/wp-content/webp-express/webp-images/doc-root/wp-content/uploads/2017/02/spicy-sardine-open-sandwich-568x379.jpg.webp.lossy.webp' 2>&1

*Output:* 
Saving file '[doc-root]/wp-content/webp-express/webp-images/doc-root/wp-content/uploads/2017/02/spicy-sardine-open-sandwich-568x379.jpg.webp.lossy.webp'
File:      [doc-root]/wp-content/uploads/2017/02/spicy-sardine-open-sandwich-568x379.jpg
Dimension: 568 x 379
Output:    45016 bytes Y-U-V-All-PSNR 39.57 41.79 42.26   40.25 dB
           (1.67 bpp)
block count:  intra4:        809  (93.63%)
              intra16:        55  (6.37%)
              skipped:         0  (0.00%)
bytes used:  header:            242  (0.5%)
             mode-partition:   4404  (9.8%)
 Residuals bytes  |segment 1|segment 2|segment 3|segment 4|  total
  intra4-coeffs:  |   31307 |      94 |     143 |     181 |   31725  (70.5%)
 intra16-coeffs:  |     290 |       6 |      62 |      80 |     438  (1.0%)
  chroma coeffs:  |    7953 |      33 |      65 |     126 |    8177  (18.2%)
    macroblocks:  |      92%|       1%|       2%|       5%|     864
      quantizer:  |      20 |      14 |      11 |      11 |
   filter level:  |      18 |       3 |       2 |      11 |
------------------+---------+---------+---------+---------+-----------------
 segments total:  |   39550 |     133 |     270 |     387 |   40340  (89.6%)

Success
Reduction: 43% (went from 77 kb to 44 kb)

Converting to lossless
Locating cwebp binaries
1 cwebp binaries found in common system locations
Checking if we have a supplied binary for OS: Darwin... We do.
We in fact have 1
A total of 2 cwebp binaries where found
Detecting versions of the cwebp binaries found (and verifying that they can be executed in the process)
Executing: /usr/local/bin/cwebp -version. Result: version: 1.0.3
Executing: [doc-root]/wp-content/plugins/webp-express/vendor/rosell-dk/webp-convert/src/Convert/Converters/Binaries/cwebp-mac12 -version
Exec failed (the cwebp binary was not found at path: [doc-root]/wp-content/plugins/webp-express/vendor/rosell-dk/webp-convert/src/Convert/Converters/Binaries/cwebp-mac12)
Trying executing the cwebs found until success. Starting with the ones with highest version number.
Creating command line options for version: 1.0.3
Trying to convert by executing the following command:
nice /usr/local/bin/cwebp -metadata none -q 80 -alpha_q '85' -near_lossless 60 -m 6 -low_memory '[doc-root]/wp-content/uploads/2017/02/spicy-sardine-open-sandwich-568x379.jpg' -o '[doc-root]/wp-content/webp-express/webp-images/doc-root/wp-content/uploads/2017/02/spicy-sardine-open-sandwich-568x379.jpg.webp.lossless.webp' 2>&1

*Output:* 
Saving file '[doc-root]/wp-content/webp-express/webp-images/doc-root/wp-content/uploads/2017/02/spicy-sardine-open-sandwich-568x379.jpg.webp.lossless.webp'
File:      [doc-root]/wp-content/uploads/2017/02/spicy-sardine-open-sandwich-568x379.jpg
Dimension: 568 x 379
Output:    187654 bytes (6.97 bpp)
Lossless-ARGB compressed size: 187654 bytes
  * Header size: 2290 bytes, image data size: 185338
  * Lossless features used: PREDICTION CROSS-COLOR-TRANSFORM SUBTRACT-GREEN
  * Precision Bits: histogram=4 transform=4 cache=10

Success
Reduction: -139% (went from 77 kb to 183 kb)

Picking lossy
cwebp succeeded :)

Converted image in 552 ms, reducing file size with 43% (went from 77 kb to 44 kb)
