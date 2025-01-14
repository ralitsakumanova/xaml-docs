---
title: Getting Started
page_title: Getting Started
description: Check our &quot;Getting Started&quot; documentation article for the RadBarcode {{ site.framework_name }} control.
slug: radbarcodeqr-getting-started
tags: getting,started
published: True
position: 1
permalink: /controls/radbarcode/oldbarcode/2d-barcodes/radbarcodeqr/radbarcodeqr-getting-started
---

# Getting Started

>important This is the documentation of the old version of the RadBarcode component, which is currently deprecated. Check out the new version [here]({%slug barcode-getting-started%}).

>In order to use __RadBarcodeQR__ in your projects you have to add references to the following two assemblies:
>	- __Telerik.Windows.Data.dll__ 
>	- __Telerik.Windows.Controls.dll__ 
>	- __Telerik.Windows.Controls.DataVisualization.dll__

## Defining RadBarcodeQR

#### __[XAML] Example 1: QR barcode definition__  
{{region xaml-radbarcodeqr-getting-started-0}}
	<telerik:RadBarcodeQR Version="20" ErrorCorrectionLevel="H" Text="Sample text" 
						  Mode="Byte" ECI="ISO8859_1" FNC1="FNC1SecondPosition" 
						  ApplicationIndicator="00" />
{{endregion}}

## See Also
* [QRCode Visual Structure]({%slug radbarcodeqr-qrcode-visual-structure%})
* [QRCode Properties]({%slug radbarcodeqr-features%})