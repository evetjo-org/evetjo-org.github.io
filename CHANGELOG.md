## v0.0.63
2024-12-13 16:15:44 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] estimator.html
    - Changes:  1 file changed, 1 insertion(+)
    - Context:
  @@ -4,0 +5 @@
  +    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><circle cx='50' cy='50' r='40' fill='%2322c55e'/></svg>">
    - Significant change: @@ -4,0 +5 @@
  [Modified] index.html
    - Changes:  1 file changed, 1 insertion(+)
    - Context:
  @@ -97,0 +98 @@
  +    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><circle cx='50' cy='50' r='40' fill='%2322c55e'/></svg>">
    - Significant change: @@ -97,0 +98 @@
  
## v0.0.62
2024-12-13 16:11:49 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] estimator.html
    - Changes:  1 file changed, 1 insertion(+), 1 deletion(-)
    - Context:
  @@ -70 +70 @@
  -                                   value="5" 
  +                                   value="8" 
    - Significant change: @@ -70 +70 @@
  
## v0.0.61
2024-12-13 16:07:52 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] estimator.html
    - Changes:  1 file changed, 1 insertion(+), 1 deletion(-)
    - Context:
  @@ -57 +57 @@
  -                                   value="23" 
  +                                   value="22" 
    - Significant change: @@ -57 +57 @@
  
## v0.0.60
2024-12-11 13:08:48 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] estimator.html
    - Changes:  1 file changed, 12 insertions(+)
    - Context:
  @@ -170,0 +171 @@
  +            const numAZs = parseInt(document.getElementById('num-azs').value);
  @@ -174,0 +176,6 @@
    - Significant change: @@ -174,0 +176,6 @@
  
## v0.0.59
2024-12-11 11:04:03 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] estimator.html
    - Changes:  1 file changed, 14 insertions(+)
    - Context:
  @@ -104,0 +105 @@
  +                            <p class="text-sm text-gray-500 mt-1">Must be between /8 and /24</p>
  @@ -105,0 +107 @@
    - Significant change: @@ -266,0 +269,12 @@
  
## v0.0.58
2024-12-10 17:26:48 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] estimator.html
    - Changes:  1 file changed, 3 insertions(+), 3 deletions(-)
    - Context:
  @@ -6 +6 @@
  -    <meta name="description" content="Calculate required top-level CIDR block (supernet) size based on your actual infrastructure needs.">
  +    <meta name="description" content="Calculate a top-level CIDR block (supernet) size for your IP-plan based on your actual infrastructure needs.">
    - Significant change: @@ -104 +104 @@
  
## v0.0.57
2024-12-10 17:20:56 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] estimator.html
    - Changes:  1 file changed, 1 insertion(+), 1 deletion(-)
    - Context:
  @@ -22 +22 @@
  -                        CIDR Calculator
  +                        CIDR Block Calculator
    - Significant change: @@ -22 +22 @@
  [Modified] index.html
    - Changes:  1 file changed, 1 insertion(+), 1 deletion(-)
    - Context:
  @@ -123 +123 @@
  -                        CIDR Estimator
  +                        CIDR Block Estimator
    - Significant change: @@ -123 +123 @@
  
## v0.0.56
2024-12-10 17:17:50 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] estimator.html
    - Changes:  1 file changed, 2 insertions(+), 2 deletions(-)
    - Context:
  @@ -6 +6 @@
  -    <meta name="description" content="Calculate required CIDR block size based on your infrastructure needs">
  +    <meta name="description" content="Calculate required top-level CIDR block (supernet) size based on your actual infrastructure needs.">
    - Significant change: @@ -18 +18 @@
  
## v0.0.55
2024-12-10 17:10:05 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 2 insertions(+), 2 deletions(-)
    - Context:
  @@ -396 +396 @@ Supernet
  -│   ├── staging
  +│   ├── qa
    - Significant change: @@ -396 +396 @@ Supernet
  
## v0.0.54
2024-12-10 17:03:18 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] estimator.html
    - Changes:  1 file changed, 1 insertion(+), 1 deletion(-)
    - Context:
  @@ -233 +233 @@
  -                        <li>To fit ${numAZs} �� /${azBlockSize} networks, we need a /${vpcBlockSize} block</li>
  +                        <li>To fit ${numAZs} × /${azBlockSize} networks, we need a /${vpcBlockSize} block</li>
    - Significant change: @@ -233 +233 @@
  [Modified] index.html
    - Changes:  1 file changed, 12 insertions(+), 62 deletions(-)
    - Context:
  @@ -394,38 +394,8 @@ Supernet
  -│   ├── bu-1
  -│   │   ├── consumer
    - Significant change: @@ -394,38 +394,8 @@ Supernet
  
## v0.0.53
2024-12-10 16:54:29 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] estimator.html
    - Changes:  1 file changed, 12 insertions(+), 12 deletions(-)
    - Context:
  @@ -101,8 +101 @@
  -                <div class="bg-blue-50 p-4 mb-4 rounded">
  -                    <h3 class="font-semibold text-blue-800 mb-2">Network Planning Breakdown:</h3>
    - Significant change: @@ -110,3 +103,3 @@
  
## v0.0.52
2024-12-10 16:46:17 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[D ] forward-calculator.html
  [Modified] index.html
    - Changes: 
    - Context:
  
    - Significant change: 
  [D ] reverse-calculator.html
  [New File] estimator.html
  [New File] index_old.html
  
## v0.0.51
2024-12-10 16:29:11 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] forward-calculator.html
    - Changes:  1 file changed, 3 insertions(+), 3 deletions(-)
    - Context:
  @@ -120,3 +120,3 @@
  -                    <a href="index.html" class="text-blue-600 hover:text-blue-800 flex items-center">
  -                        <i data-lucide="home" class="w-5 h-5 mr-1"></i>
    - Significant change: @@ -120,3 +120,3 @@
  [Modified] reverse-calculator.html
    - Changes:  1 file changed, 4 insertions(+), 4 deletions(-)
    - Context:
  @@ -20,3 +20,3 @@
  -                    <a href="index.html" class="text-blue-600 hover:text-blue-800 flex items-center">
  -                        <i data-lucide="home" class="w-5 h-5 mr-1"></i>
    - Significant change: @@ -20,3 +20,3 @@
  
## v0.0.50
2024-12-10 16:22:30 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] forward-calculator.html
    - Changes:  1 file changed, 18 insertions(+), 3 deletions(-)
    - Context:
  @@ -34 +34 @@
  -        </script>
  +    </script>
    - Significant change: @@ -726,0 +735,7 @@ Supernet
  
## v0.0.49
2024-12-10 16:18:25 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] reverse-calculator.html
    - Changes:  1 file changed, 18 insertions(+), 2 deletions(-)
    - Context:
  @@ -8,0 +9 @@
  +    <script src="https://unpkg.com/lucide@latest"></script>
  @@ -14,2 +15,10 @@
    - Significant change: @@ -324,0 +334,7 @@
  
## v0.0.48
2024-12-10 16:06:06 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] reverse-calculator.html
    - Changes:  1 file changed, 2 insertions(+), 2 deletions(-)
    - Context:
  @@ -164,2 +164,2 @@
  -            if (vpcSize > subnetSize) {
  -                vpcValidation.innerHTML = 'VPC size must be equal to or smaller than subnet size (larger network)';
    - Significant change: @@ -164,2 +164,2 @@
  
## v0.0.47
2024-12-10 16:00:14 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] reverse-calculator.html
    - Changes:  1 file changed, 37 insertions(+), 12 deletions(-)
    - Context:
  @@ -52,0 +53 @@
  +                            <p id="vpc-validation" class="text-xs text-red-600 mt-1"></p>
  @@ -156,0 +158,29 @@
    - Significant change: @@ -156,0 +158,29 @@
  
## v0.0.46
2024-12-10 15:41:44 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] reverse-calculator.html
    - Changes:  1 file changed, 73 insertions(+), 25 deletions(-)
    - Context:
  @@ -20,4 +20,10 @@
  -                        <input type="text" id="subnet-size" value="/24" 
  -                               class="mt-1 block w-full rounded-md border-gray-300 shadow-sm p-2 border"
    - Significant change: @@ -239,0 +273,8 @@
  
## v0.0.45
2024-12-10 15:29:17 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 1 insertion(+)
    - Context:
  @@ -52,0 +53 @@
  +
    - Significant change: @@ -52,0 +53 @@
  [Modified] reverse-calculator.html
    - Changes:  1 file changed, 7 insertions(+), 9 deletions(-)
    - Context:
  @@ -135,0 +136 @@
  +            const azBlockSize = Math.min(subnetSize - 1, 28); // Ensure we can fit both main and hidden subnet
  @@ -147 +148 @@
    - Significant change: @@ -160,2 +160,2 @@
  
## v0.0.44
2024-12-10 15:18:09 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 1 insertion(+), 3 deletions(-)
    - Context:
  @@ -4,3 +3,0 @@
  -
  -
    - Significant change: @@ -4,3 +3,0 @@
  
## v0.0.43
2024-12-10 15:17:02 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 1 insertion(+)
    - Context:
  @@ -5,0 +6 @@
  +
    - Significant change: @@ -5,0 +6 @@
  [Modified] reverse-calculator.html
    - Changes:  1 file changed, 131 insertions(+), 43 deletions(-)
    - Context:
  @@ -20,8 +20,4 @@
  -                        <div class="relative">
  -                            <input type="text" 
    - Significant change: @@ -149,0 +225,18 @@
  
## v0.0.42
2024-12-10 15:07:26 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 1 insertion(+)
    - Context:
  @@ -4,0 +5 @@
  +
    - Significant change: @@ -4,0 +5 @@
  [Modified] reverse-calculator.html
    - Changes:  1 file changed, 76 insertions(+), 21 deletions(-)
    - Context:
  @@ -20,3 +20,8 @@
  -                        <input type="text" id="subnet-size" value="/24" 
  -                               class="mt-1 block w-full rounded-md border-gray-300 shadow-sm p-2 border"
    - Significant change: @@ -88,0 +129,11 @@
  
## v0.0.41
2024-12-10 14:59:10 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 2 insertions(+)
    - Context:
  @@ -1,0 +2 @@
  +
  @@ -2,0 +4 @@
    - Significant change: @@ -1,0 +2 @@
  [Modified] reverse-calculator.html
    - Changes:  1 file changed, 27 insertions(+), 65 deletions(-)
    - Context:
  @@ -21 +21,2 @@
  -                               class="mt-1 block w-full rounded-md border-gray-300 shadow-sm p-2 border">
  +                               class="mt-1 block w-full rounded-md border-gray-300 shadow-sm p-2 border"
    - Significant change: @@ -140,2 +103,0 @@
  
## v0.0.40
2024-12-10 14:19:15 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 9 deletions(-)
    - Context:
  @@ -2,9 +1,0 @@
  - * CIDR Calculator - for AWS
  - * Copyright (c) 2023-2024 Even Tjosaas
    - Significant change: @@ -2,9 +1,0 @@
  
## v0.0.39
2024-12-10 14:18:11 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 2 deletions(-)
    - Context:
  @@ -12,2 +11,0 @@
  -
  -
    - Significant change: @@ -12,2 +11,0 @@
  [Modified] reverse-calculator.html
    - Changes:  1 file changed, 7 insertions(+), 104 deletions(-)
    - Context:
  @@ -29,7 +29,2 @@
  -                        <label class="block text-sm font-medium text-gray-700">Minimum VPCs</label>
  -                        <input type="number" id="min-vpcs" value="200" min="1"
    - Significant change: @@ -57,12 +51,0 @@
  
## v0.0.38
2024-12-10 14:13:05 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes: 
    - Context:
  
    - Significant change: 
  [Modified] reverse-calculator.html
    - Changes: 
    - Context:
  
    - Significant change: 
  
## v0.0.37
2024-12-10 14:04:34 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 11 insertions(+), 2 deletions(-)
    - Context:
  @@ -1,2 +1,11 @@
  -
  -
    - Significant change: @@ -1,2 +1,11 @@
  
## v0.0.36
2024-12-10 14:02:21 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 1 insertion(+)
    - Context:
  @@ -1,0 +2 @@
  +
    - Significant change: @@ -1,0 +2 @@
  
## v0.0.35
2024-12-10 13:56:21 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 1 insertion(+)
    - Context:
  @@ -0,0 +1 @@
  +
    - Significant change: @@ -0,0 +1 @@
  [Modified] reverse-calculator.html
    - Changes:  1 file changed, 88 insertions(+), 14 deletions(-)
    - Context:
  @@ -49,0 +50,7 @@
  +                <div class="bg-blue-50 p-4 mb-4 rounded">
  +                    <h3 class="font-semibold text-blue-800 mb-2">Understanding the Calculations:</h3>
    - Significant change: @@ -161,0 +165,71 @@
  
## v0.0.34
2024-12-10 12:05:53 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 1 deletion(-)
    - Context:
  @@ -1 +0,0 @@
  -
    - Significant change: @@ -1 +0,0 @@
  
## v0.0.33
2024-12-10 12:05:22 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] reverse-calculator.html
    - Changes:  1 file changed, 94 insertions(+), 92 deletions(-)
    - Context:
  @@ -5,2 +5,2 @@
  -    <title>Reverse CIDR Calculator</title>
  -    <meta name="description" content="Reverse CIDR calculator tool. Find the smallest network that contains your IP addresses.">
    - Significant change: @@ -126,13 +116,21 @@ Examples:
  
## v0.0.32
2024-12-10 11:10:19 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 1 insertion(+)
    - Context:
  @@ -0,0 +1 @@
  +
    - Significant change: @@ -0,0 +1 @@
  
## v0.0.31
2024-12-10 11:03:15 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[ D] index_original.html
  [ D] old_index.html
  [ D] sargasso.png
  
## v0.0.30
2024-12-10 10:57:43 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[New File] reverse-calculator.html
  
## v0.0.29
2024-12-10 10:52:19 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] forward-calculator.html
    - Changes:  1 file changed, 724 insertions(+), 608 deletions(-)
    - Context:
  @@ -1,4 +0,0 @@
  -<html>
  -<head>
    - Significant change: @@ -613 +729,0 @@ If you wish to save this subnetting for later, bookmark <a href="subnets.html" i
  
## v0.0.28
2024-12-10 10:41:46 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 38 insertions(+), 770 deletions(-)
    - Context:
  @@ -1,13 +1 @@
  -<!--
  - * CIDR Calculator - for AWS
    - Significant change: @@ -773,3 +45,0 @@ Supernet
  
## v0.0.27
2024-12-10 10:37:11 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[New File] forward-calculator.html
  
## v0.0.26
2024-11-25 08:50:03 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 608 insertions(+), 724 deletions(-)
    - Context:
  @@ -1,13 +1 @@
  -<!--
  - * CIDR Calculator - for AWS
    - Significant change: @@ -729,0 +613 @@ Supernet
  
## v0.0.25
2024-11-22 18:26:05 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 724 insertions(+), 659 deletions(-)
    - Context:
  @@ -1,4 +0,0 @@
  -<html>
  -<head>
    - Significant change: @@ -664 +729,0 @@ If you wish to save this subnetting for later, bookmark <a href="subnets.html" i
  
## v0.0.24
2024-11-22 18:22:09 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 9 insertions(+), 26 deletions(-)
    - Context:
  @@ -153 +153 @@ function createRow(calcbody, node, address, mask, labels, depth) {
  -  // First create the row for the current node
  +  // Create row for current node
    - Significant change: @@ -280,11 +280,2 @@ function createRow(calcbody, node, address, mask, labels, depth) {
  
## v0.0.23
2024-11-22 18:17:34 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 12 insertions(+), 12 deletions(-)
    - Context:
  @@ -301 +301,5 @@ function divide(node) {
  -  // If node already has children, create new subdivisions
  +  // Always create new child nodes, regardless of existing children
    - Significant change: @@ -303,11 +307,2 @@ function divide(node) {
  
## v0.0.22
2024-11-22 18:13:23 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 120 insertions(+), 126 deletions(-)
    - Context:
  @@ -152,8 +152,11 @@ function asciiToBin(str)
  -function createRow(calcbody, node, address, mask, labels, depth)
  -{
    - Significant change: @@ -161,5 +164,12 @@ function createRow(calcbody, node, address, mask, labels, depth)
  
## v0.0.21
2024-11-22 18:03:19 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 16 insertions(+), 5 deletions(-)
    - Context:
  @@ -306,5 +306,16 @@ function newJoin(joinnode)
  -function divide(node)
  -{
    - Significant change: @@ -306,5 +306,16 @@ function newJoin(joinnode)
  
## v0.0.20
2024-11-22 17:35:37 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 2 insertions(+)
    - Context:
  @@ -240,0 +241,2 @@ function createRow(calcbody, node, address, mask, labels, depth)
  +      // Add left padding based on subnet level to create visual hierarchy
  +      buttonContainer.style.paddingLeft = ((mask - curMask) * 20) + 'px';
    - Significant change: @@ -240,0 +241,2 @@ function createRow(calcbody, node, address, mask, labels, depth)
  
## v0.0.19
2024-11-22 17:29:52 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 70 insertions(+), 9 deletions(-)
    - Context:
  @@ -236,0 +237,6 @@ function createRow(calcbody, node, address, mask, labels, depth)
  +      // Add container div for buttons
  +      var buttonContainer = document.createElement('DIV');
    - Significant change: @@ -240,9 +246,16 @@ function createRow(calcbody, node, address, mask, labels, depth)
  
## v0.0.18
2024-11-22 16:42:08 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[New File] img/
  
## v0.0.17
2024-11-22 16:37:01 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 78 insertions(+), 113 deletions(-)
    - Context:
  @@ -13 +13,2 @@ var visibleColumns = {
  -  merge: true
  +  divide: true,
    - Significant change: @@ -617,0 +577,3 @@ If you wish to save this subnetting for later, bookmark <a href="subnets.html" i
  
## v0.0.16
2024-11-22 15:44:10 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[ D] img/0.gif
  [ D] img/1.gif
  [ D] img/10.gif
  [ D] img/11.gif
  [ D] img/12.gif
  [ D] img/13.gif
  [ D] img/14.gif
  [ D] img/15.gif
  [ D] img/16.gif
  [ D] img/17.gif
  [ D] img/18.gif
  [ D] img/19.gif
  [ D] img/2.gif
  [ D] img/20.gif
  [ D] img/21.gif
  [ D] img/22.gif
  [ D] img/23.gif
  [ D] img/24.gif
  [ D] img/25.gif
  [ D] img/26.gif
  [ D] img/27.gif
  [ D] img/28.gif
  [ D] img/29.gif
  [ D] img/3.gif
  [ D] img/30.gif
  [ D] img/31.gif
  [ D] img/32.gif
  [ D] img/4.gif
  [ D] img/5.gif
  [ D] img/6.gif
  [ D] img/7.gif
  [ D] img/8.gif
  [ D] img/9.gif
  
## v0.0.15
2024-11-22 15:35:13 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 1 insertion(+), 1 deletion(-)
    - Context:
  @@ -600 +600 @@ td a {
  -<input type="button" value="Reset" onclick="if (confirm('This will reset all subnet divisions you have made. Proceed?')) startOver();">
  +<input type="button" value="Reset" onclick="if (confirm('This will reset all subnet divisions you have made. Do you want to proceed?')) startOver();">
    - Significant change: @@ -600 +600 @@ td a {
  
## v0.0.14
2024-11-22 15:30:58 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 1 insertion(+), 3 deletions(-)
    - Context:
  @@ -648,3 +648 @@ If you wish to save this subnetting for later, bookmark <a href="subnets.html" i
  -</html>
  -
    - Significant change: @@ -648,3 +648 @@ If you wish to save this subnetting for later, bookmark <a href="subnets.html" i
  
## v0.0.13
2024-11-22 15:28:43 - [ONE+evetjosa]
  [Branch: main] Changes:\n\n[Modified] index.html
    - Changes:  1 file changed, 8 insertions(+), 9 deletions(-)
    - Context:
  @@ -466,4 +466,2 @@ function joinLevel(node, targetMask) {
  -        // Collect all immediate children of the level we're removing
  -        var childrenToKeep = [];
    - Significant change: @@ -466,4 +466,2 @@ function joinLevel(node, targetMask) {
  
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
  
