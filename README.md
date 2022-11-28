IOKitBrowser
============

Jailed iOS app that lets you see various hardware info.
[Download](https://nightly.link/BomberFish/IOKitBrowser/workflows/makefile/master)

macOS support is... there.

Uses a private API to access various hardware-related informations on iOS.
I used it to check the battery cycle count. But there are other informations hidden as well, e.g. temperature, etc.

(c) developed and copyright by Lyon Anderson
http://www.lyonanderson.org/blog/2014/02/12/ios-iokit-browser/

Layout adapted by me.
iOS 11+ only. (Sorry legacy users!)      

## Check memory type:                                                                                  

Root > NxxxAP > AppleARMPE > arm-io > AppleTxxxxIO > ans > AppleA7IOPV1 > AppleCSI > asp > ASPStorage

defaults-bits-per-cell:
* 3 = TLC
* 2 = MLC
* 1 = SLC                                                                               

## Check Battery Cycle Count

Root > NxxxAP > AppleARMPE > charger > AppleARMPMUCharger

Scroll to CycleCount.

## Warning!
Do not try to submit this to the App Store! You will be rejected. 

## Disclaimer
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
