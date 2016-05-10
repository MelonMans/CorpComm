# CorpComm

<!-- Hide/Show Text... edited source : ADDED <div> tag to wrap all text 
          Note: required properties: 1. id="helpInfo"  2. style="display: none;"  -->

            <div id="helpInfo" unselectable="on" style="display: none;">
               <p unselectable="on">Use 
                  <img src="/sites/CorpComm/SiteAssets/PowerPoint%20Navigation.JPG" unselectable="on" alt="" style="margin: 5px; width: 100px; height: 22px;"/>&#160;at the bottom of PowerPoint to view pages:</p>
               <p unselectable="on">1. Single Item</p>
               <p unselectable="on">2. Multiple Items</p>
               <p unselectable="on">3. Item Removal</p>
            </div>
            

-------------------------------------------------------------------


<!-- CorpComm button code -->

<button id="buttonTest_btn" type="button">Show/Hide Help</button>

<style type="text/css">
#buttonTest_btn {      /* Button styling */
    border: 2px solid black;
    padding: 15px 32px;
    text-align: center;
    font-size: 20px;
}
</style>

<script type="text/javascript">
document.getElementById('buttonTest_btn').onclick = function() { 
    var toggHelpWindow = document.getElementById('helpWindow');   // PowerPoint Object
    var toggHelpInfo = document.getElementById('helpInfo');                 // Text Object

    if (toggHelpWindow.style.display == 'block'){
       toggHelpWindow.style.display = 'none';            
       toggHelpInfo.style.display = 'none';
}
   else {
        toggHelpWindow.style.display = 'block';
        toggHelpInfo.style.display = 'block';
}}

</script>




<!----------------EMBEDDED POWERPOINT ----------------------------------
      Note, changes include:  1. id="helpWindow"   2. style="display: none;" -->

  <div id="helpWindow" style="display: none;" unselectable="on">   
      <iframe width="705" height="450" src="/sites/CorpComm/_layouts/15/WopiFrame.aspx?sourcedoc=%7b3828d529-e42f-4c22-8f1b-42878e4e7158%7d&amp;action=embedview&amp;wdAr=1.5675675675675675&amp;Embed=1" frameborder="0" style="display: block;"></iframe>&nbsp; 
  </div>



