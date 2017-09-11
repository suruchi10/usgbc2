

def signin():
    #Launches the specified browser and opens the specified URL in it.
    Browsers.Item[btFirefox, "", Browsers.pX64].Run("about:home")
    #Moves the mouse pointer over the 'panelSpacer' control.
    Aliases.browser.pageMozillaFirefoxStartPage.panelSpacer.HoverMouse(804, 54)
    #Navigates to the ''http://dev-dynamic-usgbc.pantheonsite.io/signin'' address.
    Aliases.browser.ToUrl("http://dev-dynamic-usgbc.pantheonsite.io/signin")
    #Compares the imageLogoSvg Stores item with the image of the Aliases.browser.pageSignInPageDynamicUsgbc.headerMainHeader.navNavbarNavbarDefault.imageLogoSvg object.
    Regions.imageLogoSvg.Check(Aliases.browser.pageSignInPageDynamicUsgbc.headerMainHeader.navNavbarNavbarDefault.imageLogoSvg)
    #Verifies the web page using the WebAccessibility5 Stores item.
    WebTesting.WebAccessibility5.Check()
    #Clicks at point (77, 14) of the 'textboxEmail' object.
    Aliases.browser.pageSignInPageDynamicUsgbc.formUsgbcCoreSigninForm.textboxEmail.Click(77, 14)
    #Sets the text 'shubh@gmail.com' in the 'textboxEmail' text editor.
    Aliases.browser.pageSignInPageDynamicUsgbc.formUsgbcCoreSigninForm.textboxEmail.SetText("shubh@gmail.com")
    #Sets the text 'shubh' in the 'passwordboxPassword' text editor.
    Aliases.browser.pageSignInPageDynamicUsgbc.formUsgbcCoreSigninForm.panelRow.panelColMd12ColXs12.panelColMd8ColMdOffset2ColXs12Us.panelUsgbcContainerInnerBox.panelUsgbcFormFieldColMd12ColXs1.panelJsFormItemFormItemJsFormTyp.passwordboxPassword.SetText("shubh")
    #Checks whether the 'idStr' property of the Aliases.browser.pageSignInPageDynamicUsgbc.formUsgbcCoreSigninForm.submitbuttonSignInContinue object equals 'edit-submit'.
    aqObject.CheckProperty(Aliases.browser.pageSignInPageDynamicUsgbc.formUsgbcCoreSigninForm.submitbuttonSignInContinue, "idStr", cmpEqual, "edit-submit")
    #Clicks the 'buttonSignInContinue' button.
    Aliases.browser.pageSignInPageDynamicUsgbc.formUsgbcCoreSigninForm.panelRow.panelColMd12ColXs12.panelColMd8ColMdOffset2ColXs12Us.buttonSignInContinue.ClickButton()
    #Waits until the browser loads the page and is ready to accept user input.
    Aliases.browser.pageAccessDeniedDynamicUsgbc.Wait()
    #Checks whether the 'Text' property of the Aliases.browser.pageSignInPageDynamicUsgbcMozill.toolbarNavBar.toolbaritemUrlbarContainer.textboxUrlbar.inputAutocompleteTextboxUrlbarIn object equals 'dev-dynamic-usgbc.pantheonsite.io/notauthorized'.
    aqObject.CheckProperty(Aliases.browser.pageSignInPageDynamicUsgbcMozill.toolbarNavBar.toolbaritemUrlbarContainer.textboxUrlbar.inputAutocompleteTextboxUrlbarIn, "Text", cmpEqual, "dev-dynamic-usgbc.pantheonsite.io/notauthorized")
    #Clicks the 'BrowserWindow' control.
    Aliases.browser.BrowserWindow.Close()
