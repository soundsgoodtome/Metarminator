Metarminator
============

The iTunes Metadata editor for the rest of us.

![Screenshot](https://raw.githubusercontent.com/x43x61x69/Metarminator/master/Screenshot.png)


Description
-----------

**Metarminator** allows you to batch edit **iTunes Metadata** of your iTunes musics and videos, whether iTunes allows you to edit them or not.

[Bug report and feedback](https://github.com/x43x61x69/Metarminator/issues) | [Follow Me on Twitter (@x43x61x69)](https://twitter.com/x43x61x69)


FAQs
----

**Q: Where can I buy Metarminator?**

**A:** You can buy it from the Mac App Store soon.

**Q: What does it do?**

**A:** Metarminator allows you to batch edit iTunes Metadata of your iTunes musics and videos, whether iTunes allows you to edit them or not. Such as your personal purchase info, Apple ID, etc.

**Q: What formats does it support?**

**A:** Currently, Metarminator supports those formats that are iTunes Metadata compatible: **MP4**, **M4A**, **M4P**, **M4V** and **M4B**.

**Q: Can I add files by drag and drop?**

**A:** Sure. Simply drag and drop them to the main window or the dock icon.

**Q: Why MP3s are not supported?**

**A:** While they are lots of tools out there can edit ID3 tags, there are only few that does iTunes Metadata. This tool was created to help people get the ability to view, edit or remove the info they wish. As MP3s is **not iTunes Metadata compatible** (it use **ID3**), it's not supported by Metarminator yet.

**Q: Are there limitations to the values?**

**A:** The limitation varies, as listed below.

* **For fields that has sting as value:** Less than **256** English characters (Excepts **lyrics**, which has no limit).
* **The fields that has number as value:** Between **0** and **65535**. Some fields might accept larger values.
* **For cover artworks:** You can add **ANY** image that supported by OS X. They will be converted and stored as **JPEG** in the metada. You can drag and drop them into the preview box or use the "Add" button.

**Q: What's that "Deep Scan" option for?**

**A:** By default, the application will only search the extra data in the first 1024 bytes to shorten the processing time. In the Deep Scan mode, it will however, search the whole file.

**Q: What's that "Scale" option for cover artwork?**

**A:** If "scale" is enabled, the artwork will be resized to **600px** before it's being stored, depends on the longest side. Exporting format can be **BMP**, **GIF**, **JPEG**, **PNG** and **TIFF**.

**Q: Does it has a fields filter?**

**A:** Yes, the right bottom corner button opens a drawer of filters. The disabled fields will not apply to the saving files. You can use the save button at the bottom of the drawer to save current filter selections.

**Q: What does the AAC type has to do with the User ID?**

A: Apple currently has 5 types of AACs, they can either be:

* **Normal:** Those that are not from Apple will be labeled as AAC files in iTunes.
* **Purchased:** Those are purchased from iTunes will be labeled as Purchased AAC. The User ID must be greater than 0 as it should be purchased by someone to be a "Purchased".
* **Matched:** Those were matched and re-downloaded from iTunes Match (iCloud) will be labeled as Matched AAC. The User ID must be greater than 0 as it should be "Matched" by someone's iCloud account to be a "Matched".
* **Mastered for iTunes:** Some of the musics are mastered for iTunes when they were sold on iTunes Store. This can be either for a Purchased AAC or a Matched AAC file. Normal AAC can't have this tag.

**Q: What does the "Remove Personal Info" feature do?**

**A:** It removes all the data I currently know that are related to personal info that might be able to trace back to you. (**Purchased by**, **Apple ID**, **Purchased date**, and **User ID**) As Apple might add anything new (and possibly hidden), the ONLY secure way to make sure a file is untraceable is to re-encode it.

**Q: Will it ever support OS X 10.8 or lower?**

**A:** No. Some APIs are only available in 10.9 and above, and Apple has made it a nightmare for developers trying to use old SDKs since Xcode 5.

**Q: I found a bug. Where can I report it?**

**A:** Thank you. Please open an issue [here](https://github.com/x43x61x69/Metarminator/issues).

**Q: I wish it to have other features.**

**A:** Sure. Please open an issue [here](https://github.com/x43x61x69/Metarminator/issues).



Changelog
---------

**v1.0:**

* Initial release.



License
-------

Copyright (C) 2014  Cai, Zhi-Wei.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

