<p><span style="font-size: 14px;">Slots are containers for images and Bridges between bones and images.In the main scene, the picture hierarchy is represented by the slot hierarchy in the hierarchy panel.As shown below, the "left forearm" is above the "left upper arm," and the effect in the main scene is that the "left forearm" covers the "left upper arm.".</span></p><p><img alt="The layers panel.png" src="http://sedn.egret.com/ueditor/20150609/5576afcb4f166.png" title="The layers panel.png"/></p><p><span style="font-size: 14px;">There are three ways to create a slot：</span></p><ol class=" list-paddingleft-2" style="list-style-type: decimal;"><li><p><span style="font-size: 14px;">Drag and drop images directly from the resources panel into the main scene . </span></p></li><li><p><span style="font-size: 14px;">Drag the image from the resources panel to any skeleton in the scene tree panel.</span></p></li><li><p><span style="font-size: 14px;">Select a skeleton and click the add slot button on the scene tree panel.</span></p></li></ol><p><span style="font-size: 14px;">&nbsp;</span></p><p><span style="font-size: 14px;">Slot characteristics：</span></p><ul class=" list-paddingleft-2" style="list-style-type: disc;"><li><p><span style="font-size: 14px;">Slots can be empty and do not contain any images.</span></p></li><li><p><span style="font-size: 14px;">A skeleton can have multiple slots under it.</span></p></li><li><p><span style="font-size: 14px;">Slots under the same skeleton can have different hierarchies when rendered in the main scene. The hierarchy is only determined by the order within the hierarchy panel.</span></p></li><li><p><span style="font-size: 14px;">There can be multiple images in one slot, but only one image can be displayed at the same time.Other images will be hidden. All images in the slot can also be hidden.</span></p></li><li><p><span style="font-size: 14px;">Slots can be removed and renamed.</span></p></li><li><p><span style="font-size: 14px;">When a slot is deleted, the images it contains are deleted along with it.</span></p></li><li><p><span style="font-size: 14px;">Slot names are unique in the same project and cannot be repeated.</span></p></li><li><p><span style="font-size: 14px;">No other slots are allowed in the slot.</span></p></li><li><p><span style="font-size: 14px;">The slot cannot contain bones.</span></p></li><li><p><span style="font-size: 14px;">The position of the slot, the zoom, the rotation parameter is actually the position of the image that's in the display, the zoom, the rotation parameter,If all images in the slot are hidden, the slot position, scale, and rotate to null.</span></p></li><li><p><span style="font-size: 14px;">Slots can be checked.</span></p></li></ul><p><br/></p>