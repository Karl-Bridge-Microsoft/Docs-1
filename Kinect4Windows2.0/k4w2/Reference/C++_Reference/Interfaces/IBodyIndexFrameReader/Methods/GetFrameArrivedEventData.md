IBodyIndexFrameReader::GetFrameArrivedEventData Method  
======================================================  

Gets the event data when a new frame arrives. <span id="syntaxSection"></span>

Syntax  
======  

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">C++</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>public:  
HRESULT GetFrameArrivedEventData(  
         WAITABLE_HANDLE waitableHandle,  
         IBodyIndexFrameArrivedEventArgs **eventData  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*waitableHandle*    
Type: WAITABLE\_HANDLE  
[in] The handle to event handler that will process the event data.  

*eventData*    
Type: IBodyIndexFrameArrivedEventArgs  
[out] The event data.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : GetFrameArrivedEventData Method
RLTitle : IBodyIndexFrameReader::GetFrameArrivedEventData Method
KeywordK : GetFrameArrivedEventData method
KeywordK : IBodyIndexFrameReader::GetFrameArrivedEventData method
KeywordF : IBodyIndexFrameReader::GetFrameArrivedEventData
KeywordF : GetFrameArrivedEventData
KeywordF : Microsoft.Kinect.kinect.IBodyIndexFrameReader.GetFrameArrivedEventData(WAITABLE_HANDLE,IBodyIndexFrameArrivedEventArgs@)
KeywordA : M:Microsoft.Kinect.kinect.IBodyIndexFrameReader.GetFrameArrivedEventData(WAITABLE_HANDLE,IBodyIndexFrameArrivedEventArgs@)
AssetID : M:Microsoft.Kinect.kinect.IBodyIndexFrameReader.GetFrameArrivedEventData(WAITABLE_HANDLE,IBodyIndexFrameArrivedEventArgs@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBodyIndexFrameReader::GetFrameArrivedEventData
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
