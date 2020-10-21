# Clickable Links
Description:

An Azure DevOps web extension for displaying clickable href links on the work item form. The links are pulled from a user-configured backing field for the control that may be either visible or hidden:

![5-clickable-links-displayed-on-form.png](https://github.com/foxeehoxee/clickable-link-control-extension/blob/main/5-clickable-links-displayed-on-form.png?raw=true)

Instructions:
- Install the custom control extension to your organization:
![2-add-the-control](https://github.com/foxeehoxee/clickable-link-control-extension/blob/main/2-add-the-control.png?raw=true)

- Configure your desired backing field for the control (i.e. Case Id)
![3-select-your-field.png](https://github.com/foxeehoxee/clickable-link-control-extension/blob/main/3-select-your-field.png?raw=true)

- Add the control to your desired work item form group (i.e. Details)
![4-configure-your-layout.png](https://github.com/foxeehoxee/clickable-link-control-extension/blob/main/4-configure-your-layout.png?raw=true)

- A clickable link will be created based upon your field's value when the work item loads. The clickable link will be updated when the work item is saved or refreshed from the server:
![5-clickable-links-displayed-on-form.png](https://github.com/foxeehoxee/clickable-link-control-extension/blob/main/5-clickable-links-displayed-on-form.png?raw=true)

- Add multiple instances of the control if you want links from multiple backing fields:
![1-configure-your-fields-controls-and-layout.png](https://github.com/foxeehoxee/clickable-link-control-extension/blob/main/1-configure-your-fields-controls-and-layout.png?raw=true)

- That's it!
