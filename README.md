# Text Binarization Groundtruth

Groundtruth for Text Binarization Models

## Processing

To prepare the images for [SAM-fine-tune](https://github.com/WangRongsheng/SAM-fine-tune), I ran this command on all of the images:
```bash
mogrify -alpha off -type TrueColor png24:*
```
To convert them all to RGB PNG files with no transparency.

## Sources


| Repo Name | Link |
| --- | --- |
| DIBCO_2009(_PRINT) | [DIBCO 2009](https://users.iit.demokritos.gr/~bgat/DIBCO2009/benchmark/) |
| DIBCO_2010 | [DIBCO 2010](https://users.iit.demokritos.gr/~bgat/H-DIBCO2010/benchmark/)
| DIBCO_2011(_PRINT) | [DIBCO 2011](https://utopia.duth.gr/~ipratika/DIBCO2011/benchmark/)
| DIBCO_2012 | [DIBCO 2012](https://utopia.duth.gr/~ipratika/HDIBCO2012/benchmark/)
| DIBCO_2013 | [DIBCO 2013](https://utopia.duth.gr/~ipratika/DIBCO2013/benchmark/)
| DIBCO_2014 | [H-DIBCO 2014](https://users.iit.demokritos.gr/~bgat/HDIBCO2014/benchmark/)
| DIBCO_2016 | [H-DIBCO 2016](https://vc.ee.duth.gr/h-dibco2016/benchmark/)
| DIBCO_2017 | [DIBCO 2017](https://vc.ee.duth.gr/dibco2017/benchmark/)
| DIBCO_2018 | [H-DIBCO 2018](https://vc.ee.duth.gr/h-dibco2018/benchmark/)
| DIBCO_2019 | [DIBCO 2019](https://vc.ee.duth.gr/dibco2019/benchmark/)
| LIVEMEMORY | [LiveMemory Dataset](https://u.pcloud.link/publink/show?code=kZ9szOXZPCgUYbO25hjjPA2bh9outpxgu4gX)
| NABUCO_(1/2) | [Nabuco Dataset](https://u.pcloud.link/publink/show?code=kZbszOXZ1DIc0qnv2q4h0Lg12JSQP0vrWqFV)
| PERSIAN | [PHIBD 2012](http://www.iapr-tc11.org/mediawiki/index.php/Persian_Heritage_Image_Binarization_Dataset_(PHIBD_2012))
| BICKLEY | [Bickley Diary Dataset](https://web.archive.org/web/20130908193811/http://www.comp.nus.edu.sg/~dfanbo/projects/BinarizationShop/dataset.htm)
| RENNES | Custom Dataset ([CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)) |

## Unused Sources

[Palm Leaf Manuscript Dataset](http://amadi.univ-lr.fr/ICFHR2016_Contest/index.php/download-123)
- The lines are accurate in path but not thickness.

[DIVA-HisDB](https://diuf.unifr.ch/main/hisdoc/diva-hisdb.html)
- Too innacurate for use here.

[SleukRith Set](https://github.com/donavaly/SleukRith-Set)
- Not enough data for use here.
