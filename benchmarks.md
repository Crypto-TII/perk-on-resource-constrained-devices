# Speed Evaluation
## Key Encapsulation Schemes
| scheme | implementation | key generation [cycles] | encapsulation [cycles] | decapsulation [cycles] |
| ------ | -------------- | ----------------------- | ---------------------- | ---------------------- |
## Signature Schemes
| scheme | implementation | key generation [cycles] | sign [cycles] | verify [cycles] |
| ------ | -------------- | ----------------------- | ------------- | --------------- |
| perk-128-fast-3 (10 executions) | m4 | AVG: 641,124 <br /> MIN: 636,522 <br /> MAX: 647,852 | AVG: 244,259,083 <br /> MIN: 240,080,987 <br /> MAX: 247,151,576 | AVG: 81,018,899 <br /> MIN: 80,648,734 <br /> MAX: 81,252,416 |
| perk-128-fast-3 (10 executions) | m4-ref | AVG: 652,357 <br /> MIN: 636,742 <br /> MAX: 676,224 | AVG: 150,050,725 <br /> MIN: 149,677,050 <br /> MAX: 150,410,030 | AVG: 82,649,625 <br /> MIN: 82,255,102 <br /> MAX: 83,015,807 |
| perk-128-fast-3 (10 executions) | ref | AVG: 703,284 <br /> MIN: 693,350 <br /> MAX: 704,462 | AVG: 217,861,620 <br /> MIN: 217,626,927 <br /> MAX: 218,055,367 | AVG: 96,646,140 <br /> MIN: 96,352,277 <br /> MAX: 97,617,624 |
| perk-128-fast-3 (10 executions) | save-16-si | AVG: 643,327 <br /> MIN: 636,630 <br /> MAX: 647,863 | AVG: 229,117,058 <br /> MIN: 226,214,515 <br /> MAX: 230,783,865 | AVG: 81,083,337 <br /> MIN: 80,789,659 <br /> MAX: 81,342,539 |
| perk-128-fast-3 (10 executions) | save-30-si | AVG: 649,474 <br /> MIN: 636,804 <br /> MAX: 676,013 | AVG: 214,556,580 <br /> MIN: 214,171,773 <br /> MAX: 214,964,438 | AVG: 80,964,763 <br /> MIN: 80,825,114 <br /> MAX: 81,166,522 |
| perk-128-fast-5 (10 executions) | m4 | AVG: 817,122 <br /> MIN: 816,945 <br /> MAX: 817,271 | AVG: 240,103,798 <br /> MIN: 231,378,252 <br /> MAX: 245,204,824 | AVG: 78,092,178 <br /> MIN: 77,829,387 <br /> MAX: 78,369,158 |
| perk-128-fast-5 (10 executions) | m4-ref | AVG: 820,063 <br /> MIN: 816,899 <br /> MAX: 847,268 | AVG: 146,970,332 <br /> MIN: 146,454,914 <br /> MAX: 147,367,260 | AVG: 79,824,842 <br /> MIN: 79,362,371 <br /> MAX: 80,296,804 |
| perk-128-fast-5 (10 executions) | ref | AVG: 909,181 <br /> MIN: 909,096 <br /> MAX: 909,231 | AVG: 215,313,420 <br /> MIN: 214,956,192 <br /> MAX: 216,156,369 | AVG: 93,688,084 <br /> MIN: 93,344,458 <br /> MAX: 94,557,907 |
| perk-128-short-3 (10 executions) | m4 | AVG: 647,327 <br /> MIN: 636,662 <br /> MAX: 676,402 | AVG: 1,335,543,404 <br /> MIN: 1,321,164,639 <br /> MAX: 1,352,544,129 | AVG: 460,150,568 <br /> MIN: 459,047,178 <br /> MAX: 461,377,581 |
| perk-128-short-3 (10 executions) | save-15-si | AVG: 643,966 <br /> MIN: 636,617 <br /> MAX: 675,754 | AVG: 1,128,170,785 <br /> MIN: 1,111,210,596 <br /> MAX: 1,142,800,708 | AVG: 460,253,517 <br /> MIN: 459,594,697 <br /> MAX: 460,776,013 |
| perk-128-short-3 (10 executions) | save-5-si | AVG: 643,381 <br /> MIN: 636,707 <br /> MAX: 647,993 | AVG: 1,284,541,840 <br /> MIN: 1,238,901,553 <br /> MAX: 1,322,707,274 | AVG: 459,923,344 <br /> MIN: 458,773,433 <br /> MAX: 460,687,789 |
| perk-128-short-5 (10 executions) | m4 | AVG: 817,151 <br /> MIN: 816,966 <br /> MAX: 817,413 | AVG: 1,250,494,949 <br /> MIN: 1,219,109,103 <br /> MAX: 1,270,423,092 | AVG: 428,115,038 <br /> MIN: 427,512,556 <br /> MAX: 428,916,065 |
| perk-192-fast-3 (10 executions) | m4 | AVG: 1,495,599 <br /> MIN: 1,490,738 <br /> MAX: 1,538,071 | AVG: 581,460,957 <br /> MIN: 566,645,842 <br /> MAX: 593,311,132 | AVG: 194,730,690 <br /> MIN: 193,938,997 <br /> MAX: 196,031,469 |
| perk-192-fast-5 (10 executions) | m4 | AVG: 1,807,515 <br /> MIN: 1,793,189 <br /> MAX: 1,852,635 | AVG: 557,744,556 <br /> MIN: 545,854,768 <br /> MAX: 565,788,951 | AVG: 186,724,618 <br /> MIN: 185,537,956 <br /> MAX: 187,857,401 |
| perk-192-short-3 (10 executions) | m4 | AVG: 1,495,637 <br /> MIN: 1,490,755 <br /> MAX: 1,538,211 | AVG: 3,264,528,448 <br /> MIN: 3,203,755,982 <br /> MAX: 3,317,332,636 | AVG: 1,177,263,213 <br /> MIN: 1,172,550,752 <br /> MAX: 1,179,722,937 |
| perk-192-short-5 (10 executions) | m4 | AVG: 1,818,132 <br /> MIN: 1,803,382 <br /> MAX: 1,852,397 | AVG: 3,031,187,216 <br /> MIN: 2,982,425,520 <br /> MAX: 3,086,807,380 | AVG: 1,098,649,851 <br /> MIN: 1,096,746,554 <br /> MAX: 1,099,635,147 |
| perk-256-fast-3 (10 executions) | m4 | AVG: 2,603,004 <br /> MIN: 2,579,354 <br /> MAX: 2,755,487 | AVG: 1,187,931,868 <br /> MIN: 1,168,761,486 <br /> MAX: 1,201,445,523 | AVG: 419,152,182 <br /> MIN: 416,610,120 <br /> MAX: 421,058,689 |
| perk-256-fast-5 (10 executions) | m4 | AVG: 3,085,672 <br /> MIN: 3,051,690 <br /> MAX: 3,183,602 | AVG: 1,134,126,923 <br /> MIN: 1,105,347,013 <br /> MAX: 1,159,010,597 | AVG: 397,926,710 <br /> MIN: 394,548,921 <br /> MAX: 399,912,514 |
| perk-256-short-3 (10 executions) | m4 | AVG: 2,591,110 <br /> MIN: 2,579,043 <br /> MAX: 2,638,074 | AVG: 6,745,553,724 <br /> MIN: 6,632,676,535 <br /> MAX: 6,815,098,918 | AVG: 2,640,599,626 <br /> MIN: 2,630,863,543 <br /> MAX: 2,645,445,163 |
| perk-256-short-5 (10 executions) | m4 | AVG: 3,074,701 <br /> MIN: 3,062,405 <br /> MAX: 3,122,879 | AVG: 6,285,075,866 <br /> MIN: 6,210,986,511 <br /> MAX: 6,412,505,844 | AVG: 2,456,525,223 <br /> MIN: 2,451,668,904 <br /> MAX: 2,460,799,260 |
# Memory Evaluation
## Key Encapsulation Schemes
| Scheme | Implementation | Key Generation [bytes] | Encapsulation [bytes] | Decapsulation [bytes] |
| ------ | -------------- | ---------------------- | --------------------- | --------------------- |
## Signature Schemes
| Scheme | Implementation | Key Generation [bytes] | Sign [bytes] | Verify [bytes] |
| ------ | -------------- | ---------------------- | ------------ | -------------- |
| perk-128-fast-3 | m4 | 7,696 | 24,020 | 20,684 |
| perk-128-fast-3 | m4-ref | 7,696 | 313,364 | 313,236 |
| perk-128-fast-3 | ref | 7,728 | 313,412 | 313,284 |
| perk-128-fast-3 | save-16-si | 7,696 | 104,924 | 20,684 |
| perk-128-fast-3 | save-30-si | 7,696 | 175,628 | 20,684 |
| perk-128-fast-5 | m4 | 9,032 | 25,160 | 21,752 |
| perk-128-fast-5 | m4-ref | 9,032 | 305,688 | 305,480 |
| perk-128-fast-5 | ref | 9,032 | 305,688 | 305,480 |
| perk-128-short-3 | m4 | 7,696 | 27,780 | 25,228 |
| perk-128-short-3 | save-15-si | 7,696 | 634,508 | 25,228 |
| perk-128-short-3 | save-5-si | 7,696 | 230,020 | 25,228 |
| perk-128-short-5 | m4 | 9,032 | 28,616 | 26,056 |
| perk-192-fast-3 | m4 | 14,952 | 47,720 | 41,352 |
| perk-192-fast-5 | m4 | 16,864 | 48,776 | 42,416 |
| perk-192-short-3 | m4 | 14,952 | 51,344 | 46,656 |
| perk-192-short-5 | m4 | 16,864 | 51,888 | 47,256 |
| perk-256-fast-3 | m4 | 25,504 | 80,304 | 69,912 |
| perk-256-fast-5 | m4 | 28,064 | 80,896 | 70,640 |
| perk-256-short-3 | m4 | 25,504 | 82,264 | 74,784 |
| perk-256-short-5 | m4 | 28,064 | 82,056 | 74,808 |
# Hashing Evaluation
## Key Encapsulation Schemes
| Scheme | Implementation | Key Generation [%] | Encapsulation [%] | Decapsulation [%] |
| ------ | -------------- | ------------------ | ----------------- | ----------------- |
## Signature Schemes
| Scheme | Implementation | Key Generation [%] | Sign [%] | Verify [%] |
| ------ | -------------- | ------------------ | -------- | ---------- |
# Size Evaluation
## Key Encapsulation Schemes
| Scheme | Implementation | .text [bytes] | .data [bytes] | .bss [bytes] | Total [bytes] |
| ------ | -------------- | ------------- | ------------- | ------------ | ------------- |
## Signature Schemes
| Scheme | Implementation | .text [bytes] | .data [bytes] | .bss [bytes] | Total [bytes] |
| ------ | -------------- | ------------- | ------------- | ------------ | ------------- |
| perk-128-fast-3 | m4 | 11,717 | 4 | 0 | 11,721 |
| perk-128-fast-3 | m4-ref | 10,457 | 4 | 0 | 10,461 |
| perk-128-fast-3 | ref | 11,053 | 4 | 0 | 11,057 |
| perk-128-fast-3 | save-16-si | 12,257 | 4 | 0 | 12,261 |
| perk-128-fast-3 | save-30-si | 11,549 | 4 | 0 | 11,553 |
| perk-128-fast-5 | m4 | 11,709 | 4 | 0 | 11,713 |
| perk-128-fast-5 | m4-ref | 10,533 | 4 | 0 | 10,537 |
| perk-128-fast-5 | ref | 11,129 | 4 | 0 | 11,133 |
| perk-128-short-3 | m4 | 24,605 | 4 | 0 | 24,609 |
| perk-128-short-3 | save-15-si | 25,121 | 4 | 0 | 25,125 |
| perk-128-short-3 | save-5-si | 25,173 | 4 | 0 | 25,177 |
| perk-128-short-5 | m4 | 24,673 | 4 | 0 | 24,677 |
| perk-192-fast-3 | m4 | 12,077 | 4 | 0 | 12,081 |
| perk-192-fast-5 | m4 | 12,017 | 4 | 0 | 12,021 |
| perk-192-short-3 | m4 | 24,009 | 4 | 0 | 24,013 |
| perk-192-short-5 | m4 | 24,649 | 4 | 0 | 24,653 |
| perk-256-fast-3 | m4 | 12,129 | 4 | 0 | 12,133 |
| perk-256-fast-5 | m4 | 12,041 | 4 | 0 | 12,045 |
| perk-256-short-3 | m4 | 31,697 | 4 | 0 | 31,701 |
| perk-256-short-5 | m4 | 32,693 | 4 | 0 | 32,697 |
