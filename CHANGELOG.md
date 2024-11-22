## v0.0.12
2024-11-22 15:21:17 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 39 insertions(+), 21 deletions(-)
    - Context:
  @@ -462,3 +462,2 @@ function joinLevel(node, targetMask) {
  -      // Store the children we want to keep
  -      var childrenToKeep = [];
    - Significant change: @@ -483,9 +507,3 @@ function collectImmediateChildren(node, collection) {
  
## v0.0.11
2024-11-22 15:02:22 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 11 insertions(+), 9 deletions(-)
    - Context:
  @@ -250 +250 @@ function createRow(calcbody, node, address, mask, labels, depth)
  -	newCell.style.textAlign = 'center';  // Keep text centered without background color
  +	newCell.style.textAlign = 'center';
    - Significant change: @@ -264,2 +264,2 @@ function createRow(calcbody, node, address, mask, labels, depth)
  
## v0.0.10
2024-11-22 14:57:06 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 41 insertions(+), 32 deletions(-)
    - Context:
  @@ -249,0 +250 @@ function createRow(calcbody, node, address, mask, labels, depth)
  +	newCell.style.textAlign = 'center';  // Keep text centered without background color
  @@ -251,5 +252,3 @@ function createRow(calcbody, node, address, mask, labels, depth)
    - Significant change: @@ -251,5 +252,3 @@ function createRow(calcbody, node, address, mask, labels, depth)
  
## v0.0.9
2024-11-22 14:48:44 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 57 insertions(+), 6 deletions(-)
    - Context:
  @@ -255 +255,20 @@ function createRow(calcbody, node, address, mask, labels, depth)
  -	  newCell.onclick = newJoin(joinnode);
  +	  // Create link for merge action
    - Significant change: @@ -255 +255,20 @@ function createRow(calcbody, node, address, mask, labels, depth)
  
## v0.0.8
2024-11-22 14:23:07 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 6 insertions(+), 11 deletions(-)
    - Context:
  @@ -488 +488 @@ P		{
  -.maskSpan {
  +.maskSpan, .maskSpanJoinable {
    - Significant change: @@ -555 +550 @@ If you wish to save this subnetting for later, bookmark <a href="subnets.html" i
  
## v0.0.7
2024-11-22 14:14:36 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 3 deletions(-)
    - Context:
  @@ -544,3 +543,0 @@ If you wish to save this subnetting for later, bookmark <a href="subnets.html" i
  -</td>
  -<td align="right">
    - Significant change: @@ -544,3 +543,0 @@ If you wish to save this subnetting for later, bookmark <a href="subnets.html" i
  
## v0.0.6
2024-11-22 14:12:44 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 5 insertions(+), 4 deletions(-)
    - Context:
  @@ -238 +238 @@ function createRow(calcbody, node, address, mask, labels, depth)
  -    /* merge column (renamed from join) */
  +    /* merge column */
    - Significant change: @@ -253,2 +253 @@ function createRow(calcbody, node, address, mask, labels, depth)
  
## v0.0.5
2024-11-22 14:10:20 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 1 insertion(+), 21 deletions(-)
    - Context:
  @@ -259,4 +259 @@ function createRow(calcbody, node, address, mask, labels, depth)
  -	var newImg = document.createElement('IMG');
  -	newImg.src = 'img/'+mask+'.gif';
    - Significant change: @@ -259,4 +259 @@ function createRow(calcbody, node, address, mask, labels, depth)
  
## v0.0.4
2024-11-22 14:06:13 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 18 insertions(+), 31 deletions(-)
    - Context:
  @@ -13,2 +13 @@ var visibleColumns = {
  -  divide: true,
  -  join: true,
    - Significant change: @@ -595 +582 @@ If you wish to save this subnetting for later, bookmark <a href="subnets.html" i
  
## v0.0.3
2024-11-22 14:01:59 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 3 insertions(+), 4 deletions(-)
    - Context:
  @@ -100,0 +101 @@ function recreateTables()
  +
  @@ -568,2 +569 @@ P		{
    - Significant change: @@ -595,2 +595 @@ If you wish to save this subnetting for later, bookmark <a href="subnets.html" i
  [New File] index_original.html
  
## v0.0.2
2024-11-22 11:47:41 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 2 insertions(+)
    - Context:
  @@ -610,0 +611,2 @@ If you wish to save this subnetting for later, bookmark <a href="subnets.html" i
  +
  +
    - Significant change: @@ -610,0 +611,2 @@ If you wish to save this subnetting for later, bookmark <a href="subnets.html" i
  
## v0.0.1
2024-11-22 11:37:52 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[ D] 0.gif
  [ D] 1.gif
  [ D] 10.gif
  [ D] 11.gif
  [ D] 12.gif
  [ D] 13.gif
  [ D] 14.gif
  [ D] 15.gif
  [ D] 16.gif
  [ D] 17.gif
  [ D] 18.gif
  [ D] 19.gif
  [ D] 2.gif
  [ D] 20.gif
  [ D] 21.gif
  [ D] 22.gif
  [ D] 23.gif
  [ D] 24.gif
  [ D] 25.gif
  [ D] 26.gif
  [ D] 27.gif
  [ D] 28.gif
  [ D] 29.gif
  [ D] 3.gif
  [ D] 30.gif
  [ D] 31.gif
  [ D] 32.gif
  [ D] 4.gif
  [ D] 5.gif
  [ D] 6.gif
  [ D] 7.gif
  [ D] 8.gif
  [ D] 9.gif
  [New File] img/
  
