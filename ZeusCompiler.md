# GMAssetCompiler.CheckLicense
  ## Members
    * Byte[] get_MD5()
    * Void set_MD5(Byte[])
    * Int32 get_CRC()
    * Void set_CRC(Int32)
    * System.Collections.Generic.Dictionary`2[System.String,System.String] get_License()
    * Void set_License(System.Collections.Generic.Dictionary`2[System.String,System.String])
    * Byte[] CreateByteArrayFromHex(System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String)
    * Byte[] MD5
    * Int32 CRC
    * System.Collections.Generic.Dictionary`2[System.String,System.String] License
# GMAssetCompiler.GMAudioGroup
  ## Members
    * System.String get_Name()
    * Int32 get_GroupIndex()
    * Int64 get_TargetMask()
    * Void SetFromConfig(System.Collections.Generic.Dictionary`2[System.String,System.String])
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, Int32, System.Xml.XmlNode)
    * System.String Name
    * Int32 GroupIndex
    * Int64 TargetMask
# GMAssetCompiler.GMResource
  ## Members
    * System.String get_Name()
    * System.Guid get_GUID()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.Guid GUID
# GMAssetCompiler.GMMacro
  ## Members
    * System.String get_ResourcePath()
    * System.String get_filename()
    * System.String get_Config()
    * System.String get_Name()
    * System.Guid get_GUID()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * System.String ResourcePath
    * System.String filename
    * System.String Config
    * System.String Name
    * System.Guid GUID
# GMAssetCompiler.eShaderType
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.eShaderType GLSLES
    * GMAssetCompiler.eShaderType GLSL
    * GMAssetCompiler.eShaderType HLSL9
    * GMAssetCompiler.eShaderType HLSL11
    * GMAssetCompiler.eShaderType PSSL
    * GMAssetCompiler.eShaderType CG
    * GMAssetCompiler.eShaderType CG_PS3
# GMAssetCompiler.GMShader
  ## Members
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Void set_ShaderType(GMAssetCompiler.eShaderType)
    * Int32 get_CompiledIndex()
    * Void set_CompiledIndex(Int32)
    * System.String get_SourceFileName()
    * Void set_SourceFileName(System.String)
    * System.String get_Shader()
    * Void set_Shader(System.String)
    * System.String get_ShaderPrefix()
    * Void set_ShaderPrefix(System.String)
    * System.String get_Raw_Vertex_Shader()
    * Void set_Raw_Vertex_Shader(System.String)
    * System.String get_Raw_Fragment_Shader()
    * Void set_Raw_Fragment_Shader(System.String)
    * System.String get_VertexShader_ES()
    * System.String get_FragmentShader_ES()
    * System.String get_VertexShader()
    * System.String get_FragmentShader()
    * System.String get_HLSL9_VertexShader()
    * System.String get_HLSL9_PixelShader()
    * Byte[] get_HLSL11_VertexShader()
    * Void set_HLSL11_VertexShader(Byte[])
    * Byte[] get_HLSL11_PixelShader()
    * Void set_HLSL11_PixelShader(Byte[])
    * Byte[] get_PSSL_VertexShader()
    * Void set_PSSL_VertexShader(Byte[])
    * Byte[] get_PSSL_PixelShader()
    * Void set_PSSL_PixelShader(Byte[])
    * Byte[] get_CG_VertexShader()
    * Void set_CG_VertexShader(Byte[])
    * Byte[] get_CG_PixelShader()
    * Void set_CG_PixelShader(Byte[])
    * Byte[] get_CG_PS3_VertexShader()
    * Void set_CG_PS3_VertexShader(Byte[])
    * Byte[] get_CG_PS3_PixelShader()
    * Void set_CG_PS3_PixelShader(Byte[])
    * System.Collections.Generic.List`1[System.String] get_VSAttributes()
    * Void UpdateShaderFiles(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.List`1[System.String])
    * System.String GetShader(eWhichShader)
    * System.String GetVertexShader()
    * System.String GetFragmentShader()
    * Void CompileHLSLfromGLSLES()
    * Void CompileHLSL11fromGLSLES()
    * Void CompileHLSL11()
    * Void CompilePSSL()
    * Void CompilePSSLfromGLSLES()
    * Void CompileCG()
    * Void CompileCGfromGLSLES()
    * Void CompileCG_PS3()
    * Void CompileCG_PS3fromGLSLES()
    * System.String get_Name()
    * System.Guid get_GUID()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.String, System.String)
    * Void .ctor(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void .ctor(System.String)
    * GMAssetCompiler.eShaderType ShaderType
    * Int32 CompiledIndex
    * System.String SourceFileName
    * System.String Shader
    * System.String ShaderPrefix
    * System.String Raw_Vertex_Shader
    * System.String Raw_Fragment_Shader
    * System.String VertexShader_ES
    * System.String FragmentShader_ES
    * System.String VertexShader
    * System.String FragmentShader
    * System.String HLSL9_VertexShader
    * System.String HLSL9_PixelShader
    * Byte[] HLSL11_VertexShader
    * Byte[] HLSL11_PixelShader
    * Byte[] PSSL_VertexShader
    * Byte[] PSSL_PixelShader
    * Byte[] CG_VertexShader
    * Byte[] CG_PixelShader
    * Byte[] CG_PS3_VertexShader
    * Byte[] CG_PS3_PixelShader
    * System.Collections.Generic.List`1[System.String] VSAttributes
    * System.String Name
    * System.Guid GUID
    * System.String name
    * System.String VShaderPreamble
    * System.String FShaderPreamble
    * System.String VShaderPreamble_GLSL
    * System.String FShaderPreamble_GLSL
    * System.String VShaderPreamble_HLSL9
    * System.String PShaderPreamble_HLSL9
    * System.String VShaderPreamble_HLSL11
    * System.String PShaderPreamble_HLSL11
    * System.String VShaderPreamble_PSSL
    * System.String PShaderPreamble_PSSL
    * System.String VShaderPreamble_CG
    * System.String PShaderPreamble_CG
    * System.String VShaderPreamble_CG_PS3
    * System.String PShaderPreamble_CG_PS3
    * System.String HLSLtoPSSL_preamble
    * System.String HLSLtoCG_preamble
    * System.String HLSLtoCG_PS3_preamble
    * GMAssetCompiler.GMShader+eWhichShader
# GMAssetCompiler.GMShader+eWhichShader
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * eWhichShader GLSLES_Fragment
    * eWhichShader GLSLES_Vertex
    * eWhichShader GLSL_Fragment
    * eWhichShader GLSL_Vertex
    * eWhichShader HLSL9_Pixel
    * eWhichShader HLSL9_Vertex
    * eWhichShader HLSL11_Pixel
    * eWhichShader HLSL11_Vertex
    * eWhichShader PSSL_Pixel
    * eWhichShader PSSL_Vertex
    * eWhichShader CG_Pixel
    * eWhichShader CG_Vertex
    * eWhichShader CG_PS3_Pixel
    * eWhichShader CG_PS3_Vertex
    * eWhichShader NumShaderTypes
# GMAssetCompiler.GMTextureGroup
  ## Members
    * Boolean get_Autocrop()
    * Int32 get_Border()
    * System.String get_GroupName()
    * System.String get_ParentGUID()
    * System.String get_ParentName()
    * Void set_ParentName(System.String)
    * System.String get_GroupGUID()
    * Boolean get_Scaled()
    * Int64 get_TargetsMask()
    * Void SetParentName(System.Collections.Generic.List`1[GMAssetCompiler.GMTextureGroup])
    * System.String get_Name()
    * System.Guid get_GUID()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Boolean Autocrop
    * Int32 Border
    * System.String GroupName
    * System.String ParentGUID
    * System.String ParentName
    * System.String GroupGUID
    * Boolean Scaled
    * Int64 TargetsMask
    * System.String Name
    * System.Guid GUID
# GMAssetCompiler.Form1
  ## Members
    * Void AddSprites()
    * Void AddExtensions()
    * Void AddSounds()
    * Void AddBackgrounds()
    * Void AddPaths()
    * Void AddScripts()
    * Void AddFonts()
    * Void AddTimeLines()
    * Void AddObjects()
    * Void AddRooms()
    * Void AddDataFiles()
    * Void AddLibraries()
    * Void AddRoomOrder()
    * Void AddOptions()
    * Byte[] createOutTexture(System.Drawing.Image, GMAssetCompiler.eSquishFlags, System.Drawing.Image ByRef, GMAssetCompiler.eTexType)
    * Byte[] CompressImageRaw(System.Drawing.Image)
    * System.Windows.Forms.IButtonControl get_AcceptButton()
    * Void set_AcceptButton(System.Windows.Forms.IButtonControl)
    * System.Windows.Forms.Form get_ActiveMdiChild()
    * Boolean get_AllowTransparency()
    * Void set_AllowTransparency(Boolean)
    * Boolean get_AutoScale()
    * Void set_AutoScale(Boolean)
    * System.Drawing.Size get_AutoScaleBaseSize()
    * Void set_AutoScaleBaseSize(System.Drawing.Size)
    * Boolean get_AutoScroll()
    * Void set_AutoScroll(Boolean)
    * Boolean get_AutoSize()
    * Void set_AutoSize(Boolean)
    * Void add_AutoSizeChanged(System.EventHandler)
    * Void remove_AutoSizeChanged(System.EventHandler)
    * System.Windows.Forms.AutoSizeMode get_AutoSizeMode()
    * Void set_AutoSizeMode(System.Windows.Forms.AutoSizeMode)
    * System.Windows.Forms.AutoValidate get_AutoValidate()
    * Void set_AutoValidate(System.Windows.Forms.AutoValidate)
    * Void add_AutoValidateChanged(System.EventHandler)
    * Void remove_AutoValidateChanged(System.EventHandler)
    * System.Drawing.Color get_BackColor()
    * Void set_BackColor(System.Drawing.Color)
    * System.Windows.Forms.FormBorderStyle get_FormBorderStyle()
    * Void set_FormBorderStyle(System.Windows.Forms.FormBorderStyle)
    * System.Windows.Forms.IButtonControl get_CancelButton()
    * Void set_CancelButton(System.Windows.Forms.IButtonControl)
    * System.Drawing.Size get_ClientSize()
    * Void set_ClientSize(System.Drawing.Size)
    * Boolean get_ControlBox()
    * Void set_ControlBox(Boolean)
    * System.Drawing.Rectangle get_DesktopBounds()
    * Void set_DesktopBounds(System.Drawing.Rectangle)
    * System.Drawing.Point get_DesktopLocation()
    * Void set_DesktopLocation(System.Drawing.Point)
    * System.Windows.Forms.DialogResult get_DialogResult()
    * Void set_DialogResult(System.Windows.Forms.DialogResult)
    * Boolean get_HelpButton()
    * Void set_HelpButton(Boolean)
    * Void add_HelpButtonClicked(System.ComponentModel.CancelEventHandler)
    * Void remove_HelpButtonClicked(System.ComponentModel.CancelEventHandler)
    * System.Drawing.Icon get_Icon()
    * Void set_Icon(System.Drawing.Icon)
    * Boolean get_IsMdiChild()
    * Boolean get_IsMdiContainer()
    * Void set_IsMdiContainer(Boolean)
    * Boolean get_IsRestrictedWindow()
    * Boolean get_KeyPreview()
    * Void set_KeyPreview(Boolean)
    * System.Drawing.Point get_Location()
    * Void set_Location(System.Drawing.Point)
    * Void add_MaximizedBoundsChanged(System.EventHandler)
    * Void remove_MaximizedBoundsChanged(System.EventHandler)
    * System.Drawing.Size get_MaximumSize()
    * Void set_MaximumSize(System.Drawing.Size)
    * Void add_MaximumSizeChanged(System.EventHandler)
    * Void remove_MaximumSizeChanged(System.EventHandler)
    * System.Windows.Forms.MenuStrip get_MainMenuStrip()
    * Void set_MainMenuStrip(System.Windows.Forms.MenuStrip)
    * System.Windows.Forms.Padding get_Margin()
    * Void set_Margin(System.Windows.Forms.Padding)
    * Void add_MarginChanged(System.EventHandler)
    * Void remove_MarginChanged(System.EventHandler)
    * System.Windows.Forms.MainMenu get_Menu()
    * Void set_Menu(System.Windows.Forms.MainMenu)
    * System.Drawing.Size get_MinimumSize()
    * Void set_MinimumSize(System.Drawing.Size)
    * Void add_MinimumSizeChanged(System.EventHandler)
    * Void remove_MinimumSizeChanged(System.EventHandler)
    * Boolean get_MaximizeBox()
    * Void set_MaximizeBox(Boolean)
    * System.Windows.Forms.Form[] get_MdiChildren()
    * System.Windows.Forms.Form get_MdiParent()
    * Void set_MdiParent(System.Windows.Forms.Form)
    * System.Windows.Forms.MainMenu get_MergedMenu()
    * Boolean get_MinimizeBox()
    * Void set_MinimizeBox(Boolean)
    * Boolean get_Modal()
    * Double get_Opacity()
    * Void set_Opacity(Double)
    * System.Windows.Forms.Form[] get_OwnedForms()
    * System.Windows.Forms.Form get_Owner()
    * Void set_Owner(System.Windows.Forms.Form)
    * System.Drawing.Rectangle get_RestoreBounds()
    * Boolean get_RightToLeftLayout()
    * Void set_RightToLeftLayout(Boolean)
    * Boolean get_ShowInTaskbar()
    * Void set_ShowInTaskbar(Boolean)
    * Boolean get_ShowIcon()
    * Void set_ShowIcon(Boolean)
    * System.Drawing.Size get_Size()
    * Void set_Size(System.Drawing.Size)
    * System.Windows.Forms.SizeGripStyle get_SizeGripStyle()
    * Void set_SizeGripStyle(System.Windows.Forms.SizeGripStyle)
    * System.Windows.Forms.FormStartPosition get_StartPosition()
    * Void set_StartPosition(System.Windows.Forms.FormStartPosition)
    * Int32 get_TabIndex()
    * Void set_TabIndex(Int32)
    * Void add_TabIndexChanged(System.EventHandler)
    * Void remove_TabIndexChanged(System.EventHandler)
    * Boolean get_TabStop()
    * Void set_TabStop(Boolean)
    * Void add_TabStopChanged(System.EventHandler)
    * Void remove_TabStopChanged(System.EventHandler)
    * System.String get_Text()
    * Void set_Text(System.String)
    * Boolean get_TopLevel()
    * Void set_TopLevel(Boolean)
    * Boolean get_TopMost()
    * Void set_TopMost(Boolean)
    * System.Drawing.Color get_TransparencyKey()
    * Void set_TransparencyKey(System.Drawing.Color)
    * System.Windows.Forms.FormWindowState get_WindowState()
    * Void set_WindowState(System.Windows.Forms.FormWindowState)
    * Void add_Activated(System.EventHandler)
    * Void remove_Activated(System.EventHandler)
    * Void add_Closing(System.ComponentModel.CancelEventHandler)
    * Void remove_Closing(System.ComponentModel.CancelEventHandler)
    * Void add_Closed(System.EventHandler)
    * Void remove_Closed(System.EventHandler)
    * Void add_Deactivate(System.EventHandler)
    * Void remove_Deactivate(System.EventHandler)
    * Void add_FormClosing(System.Windows.Forms.FormClosingEventHandler)
    * Void remove_FormClosing(System.Windows.Forms.FormClosingEventHandler)
    * Void add_FormClosed(System.Windows.Forms.FormClosedEventHandler)
    * Void remove_FormClosed(System.Windows.Forms.FormClosedEventHandler)
    * Void add_Load(System.EventHandler)
    * Void remove_Load(System.EventHandler)
    * Void add_MdiChildActivate(System.EventHandler)
    * Void remove_MdiChildActivate(System.EventHandler)
    * Void add_MenuComplete(System.EventHandler)
    * Void remove_MenuComplete(System.EventHandler)
    * Void add_MenuStart(System.EventHandler)
    * Void remove_MenuStart(System.EventHandler)
    * Void add_InputLanguageChanged(System.Windows.Forms.InputLanguageChangedEventHandler)
    * Void remove_InputLanguageChanged(System.Windows.Forms.InputLanguageChangedEventHandler)
    * Void add_InputLanguageChanging(System.Windows.Forms.InputLanguageChangingEventHandler)
    * Void remove_InputLanguageChanging(System.Windows.Forms.InputLanguageChangingEventHandler)
    * Void add_RightToLeftLayoutChanged(System.EventHandler)
    * Void remove_RightToLeftLayoutChanged(System.EventHandler)
    * Void add_Shown(System.EventHandler)
    * Void remove_Shown(System.EventHandler)
    * Void Activate()
    * Void AddOwnedForm(System.Windows.Forms.Form)
    * Void Close()
    * Void LayoutMdi(System.Windows.Forms.MdiLayout)
    * Void add_DpiChanged(System.Windows.Forms.DpiChangedEventHandler)
    * Void remove_DpiChanged(System.Windows.Forms.DpiChangedEventHandler)
    * Void RemoveOwnedForm(System.Windows.Forms.Form)
    * Void add_ResizeBegin(System.EventHandler)
    * Void remove_ResizeBegin(System.EventHandler)
    * Void add_ResizeEnd(System.EventHandler)
    * Void remove_ResizeEnd(System.EventHandler)
    * Void SetDesktopBounds(Int32, Int32, Int32, Int32)
    * Void SetDesktopLocation(Int32, Int32)
    * Void Show(System.Windows.Forms.IWin32Window)
    * System.Windows.Forms.DialogResult ShowDialog()
    * System.Windows.Forms.DialogResult ShowDialog(System.Windows.Forms.IWin32Window)
    * System.String ToString()
    * Boolean ValidateChildren()
    * Boolean ValidateChildren(System.Windows.Forms.ValidationConstraints)
    * System.Drawing.SizeF get_AutoScaleDimensions()
    * Void set_AutoScaleDimensions(System.Drawing.SizeF)
    * System.Windows.Forms.AutoScaleMode get_AutoScaleMode()
    * Void set_AutoScaleMode(System.Windows.Forms.AutoScaleMode)
    * Void add_AutoValidateChanged(System.EventHandler)
    * Void remove_AutoValidateChanged(System.EventHandler)
    * System.Windows.Forms.BindingContext get_BindingContext()
    * Void set_BindingContext(System.Windows.Forms.BindingContext)
    * System.Windows.Forms.Control get_ActiveControl()
    * Void set_ActiveControl(System.Windows.Forms.Control)
    * System.Drawing.SizeF get_CurrentAutoScaleDimensions()
    * System.Windows.Forms.Form get_ParentForm()
    * Void PerformAutoScale()
    * Boolean Validate()
    * Boolean Validate(Boolean)
    * System.Drawing.Size get_AutoScrollMargin()
    * Void set_AutoScrollMargin(System.Drawing.Size)
    * System.Drawing.Point get_AutoScrollPosition()
    * Void set_AutoScrollPosition(System.Drawing.Point)
    * System.Drawing.Size get_AutoScrollMinSize()
    * Void set_AutoScrollMinSize(System.Drawing.Size)
    * System.Drawing.Rectangle get_DisplayRectangle()
    * System.Windows.Forms.HScrollProperties get_HorizontalScroll()
    * System.Windows.Forms.VScrollProperties get_VerticalScroll()
    * DockPaddingEdges get_DockPadding()
    * Void ScrollControlIntoView(System.Windows.Forms.Control)
    * Void add_Scroll(System.Windows.Forms.ScrollEventHandler)
    * Void remove_Scroll(System.Windows.Forms.ScrollEventHandler)
    * Void SetAutoScrollMargin(Int32, Int32)
    * System.Windows.Forms.AccessibleObject get_AccessibilityObject()
    * System.String get_AccessibleDefaultActionDescription()
    * Void set_AccessibleDefaultActionDescription(System.String)
    * System.String get_AccessibleDescription()
    * Void set_AccessibleDescription(System.String)
    * System.String get_AccessibleName()
    * Void set_AccessibleName(System.String)
    * System.Windows.Forms.AccessibleRole get_AccessibleRole()
    * Void set_AccessibleRole(System.Windows.Forms.AccessibleRole)
    * Boolean get_AllowDrop()
    * Void set_AllowDrop(Boolean)
    * System.Windows.Forms.AnchorStyles get_Anchor()
    * Void set_Anchor(System.Windows.Forms.AnchorStyles)
    * Void add_AutoSizeChanged(System.EventHandler)
    * Void remove_AutoSizeChanged(System.EventHandler)
    * System.Drawing.Point get_AutoScrollOffset()
    * Void set_AutoScrollOffset(System.Drawing.Point)
    * System.Windows.Forms.Layout.LayoutEngine get_LayoutEngine()
    * Void add_BackColorChanged(System.EventHandler)
    * Void remove_BackColorChanged(System.EventHandler)
    * System.Drawing.Image get_BackgroundImage()
    * Void set_BackgroundImage(System.Drawing.Image)
    * Void add_BackgroundImageChanged(System.EventHandler)
    * Void remove_BackgroundImageChanged(System.EventHandler)
    * System.Windows.Forms.ImageLayout get_BackgroundImageLayout()
    * Void set_BackgroundImageLayout(System.Windows.Forms.ImageLayout)
    * Void add_BackgroundImageLayoutChanged(System.EventHandler)
    * Void remove_BackgroundImageLayoutChanged(System.EventHandler)
    * Void ResetBindings()
    * Void add_BindingContextChanged(System.EventHandler)
    * Void remove_BindingContextChanged(System.EventHandler)
    * Int32 get_Bottom()
    * System.Drawing.Rectangle get_Bounds()
    * Void set_Bounds(System.Drawing.Rectangle)
    * Boolean get_CanFocus()
    * Boolean get_CanSelect()
    * Boolean get_Capture()
    * Void set_Capture(Boolean)
    * Boolean get_CausesValidation()
    * Void set_CausesValidation(Boolean)
    * Void add_CausesValidationChanged(System.EventHandler)
    * Void remove_CausesValidationChanged(System.EventHandler)
    * System.Drawing.Rectangle get_ClientRectangle()
    * System.Drawing.Size get_ClientSize()
    * Void set_ClientSize(System.Drawing.Size)
    * Void add_ClientSizeChanged(System.EventHandler)
    * Void remove_ClientSizeChanged(System.EventHandler)
    * System.String get_CompanyName()
    * Boolean get_ContainsFocus()
    * System.Windows.Forms.ContextMenu get_ContextMenu()
    * Void set_ContextMenu(System.Windows.Forms.ContextMenu)
    * Void add_ContextMenuChanged(System.EventHandler)
    * Void remove_ContextMenuChanged(System.EventHandler)
    * System.Windows.Forms.ContextMenuStrip get_ContextMenuStrip()
    * Void set_ContextMenuStrip(System.Windows.Forms.ContextMenuStrip)
    * Void add_ContextMenuStripChanged(System.EventHandler)
    * Void remove_ContextMenuStripChanged(System.EventHandler)
    * ControlCollection get_Controls()
    * Boolean get_Created()
    * System.Windows.Forms.Cursor get_Cursor()
    * Void set_Cursor(System.Windows.Forms.Cursor)
    * Void add_CursorChanged(System.EventHandler)
    * Void remove_CursorChanged(System.EventHandler)
    * System.Windows.Forms.ControlBindingsCollection get_DataBindings()
    * Int32 get_DeviceDpi()
    * Boolean get_IsDisposed()
    * Boolean get_Disposing()
    * System.Windows.Forms.DockStyle get_Dock()
    * Void set_Dock(System.Windows.Forms.DockStyle)
    * Void add_DockChanged(System.EventHandler)
    * Void remove_DockChanged(System.EventHandler)
    * Boolean get_Enabled()
    * Void set_Enabled(Boolean)
    * Void add_EnabledChanged(System.EventHandler)
    * Void remove_EnabledChanged(System.EventHandler)
    * Boolean get_Focused()
    * System.Drawing.Font get_Font()
    * Void set_Font(System.Drawing.Font)
    * Void add_FontChanged(System.EventHandler)
    * Void remove_FontChanged(System.EventHandler)
    * System.Drawing.Color get_ForeColor()
    * Void set_ForeColor(System.Drawing.Color)
    * Void add_ForeColorChanged(System.EventHandler)
    * Void remove_ForeColorChanged(System.EventHandler)
    * System.Drawing.Size GetPreferredSize(System.Drawing.Size)
    * IntPtr get_Handle()
    * Boolean get_HasChildren()
    * Int32 get_Height()
    * Void set_Height(Int32)
    * Boolean get_IsHandleCreated()
    * Boolean get_InvokeRequired()
    * Boolean get_IsAccessible()
    * Void set_IsAccessible(Boolean)
    * Boolean get_IsMirrored()
    * Int32 get_Left()
    * Void set_Left(Int32)
    * System.Drawing.Point get_Location()
    * Void set_Location(System.Drawing.Point)
    * Void add_LocationChanged(System.EventHandler)
    * Void remove_LocationChanged(System.EventHandler)
    * System.Windows.Forms.Padding get_Margin()
    * Void set_Margin(System.Windows.Forms.Padding)
    * Void add_MarginChanged(System.EventHandler)
    * Void remove_MarginChanged(System.EventHandler)
    * System.String get_Name()
    * Void set_Name(System.String)
    * System.Windows.Forms.Control get_Parent()
    * Void set_Parent(System.Windows.Forms.Control)
    * System.String get_ProductName()
    * System.String get_ProductVersion()
    * Boolean get_RecreatingHandle()
    * System.Drawing.Region get_Region()
    * Void set_Region(System.Drawing.Region)
    * Void add_RegionChanged(System.EventHandler)
    * Void remove_RegionChanged(System.EventHandler)
    * Int32 get_Right()
    * System.Windows.Forms.RightToLeft get_RightToLeft()
    * Void set_RightToLeft(System.Windows.Forms.RightToLeft)
    * Void add_RightToLeftChanged(System.EventHandler)
    * Void remove_RightToLeftChanged(System.EventHandler)
    * System.ComponentModel.ISite get_Site()
    * Void set_Site(System.ComponentModel.ISite)
    * System.Drawing.Size get_Size()
    * Void set_Size(System.Drawing.Size)
    * Void add_SizeChanged(System.EventHandler)
    * Void remove_SizeChanged(System.EventHandler)
    * Int32 get_TabIndex()
    * Void set_TabIndex(Int32)
    * Void add_TabIndexChanged(System.EventHandler)
    * Void remove_TabIndexChanged(System.EventHandler)
    * Boolean get_TabStop()
    * Void set_TabStop(Boolean)
    * Void add_TabStopChanged(System.EventHandler)
    * Void remove_TabStopChanged(System.EventHandler)
    * System.Object get_Tag()
    * Void set_Tag(System.Object)
    * Void add_TextChanged(System.EventHandler)
    * Void remove_TextChanged(System.EventHandler)
    * Int32 get_Top()
    * Void set_Top(Int32)
    * System.Windows.Forms.Control get_TopLevelControl()
    * Boolean get_UseWaitCursor()
    * Void set_UseWaitCursor(Boolean)
    * Boolean get_Visible()
    * Void set_Visible(Boolean)
    * Void add_VisibleChanged(System.EventHandler)
    * Void remove_VisibleChanged(System.EventHandler)
    * Int32 get_Width()
    * Void set_Width(Int32)
    * System.Windows.Forms.IWindowTarget get_WindowTarget()
    * Void set_WindowTarget(System.Windows.Forms.IWindowTarget)
    * Void add_Click(System.EventHandler)
    * Void remove_Click(System.EventHandler)
    * Void add_ControlAdded(System.Windows.Forms.ControlEventHandler)
    * Void remove_ControlAdded(System.Windows.Forms.ControlEventHandler)
    * Void add_ControlRemoved(System.Windows.Forms.ControlEventHandler)
    * Void remove_ControlRemoved(System.Windows.Forms.ControlEventHandler)
    * Void add_DragDrop(System.Windows.Forms.DragEventHandler)
    * Void remove_DragDrop(System.Windows.Forms.DragEventHandler)
    * Void add_DragEnter(System.Windows.Forms.DragEventHandler)
    * Void remove_DragEnter(System.Windows.Forms.DragEventHandler)
    * Void add_DragOver(System.Windows.Forms.DragEventHandler)
    * Void remove_DragOver(System.Windows.Forms.DragEventHandler)
    * Void add_DragLeave(System.EventHandler)
    * Void remove_DragLeave(System.EventHandler)
    * Void add_GiveFeedback(System.Windows.Forms.GiveFeedbackEventHandler)
    * Void remove_GiveFeedback(System.Windows.Forms.GiveFeedbackEventHandler)
    * Void add_HandleCreated(System.EventHandler)
    * Void remove_HandleCreated(System.EventHandler)
    * Void add_HandleDestroyed(System.EventHandler)
    * Void remove_HandleDestroyed(System.EventHandler)
    * Void add_HelpRequested(System.Windows.Forms.HelpEventHandler)
    * Void remove_HelpRequested(System.Windows.Forms.HelpEventHandler)
    * Void add_Invalidated(System.Windows.Forms.InvalidateEventHandler)
    * Void remove_Invalidated(System.Windows.Forms.InvalidateEventHandler)
    * System.Drawing.Size get_PreferredSize()
    * System.Windows.Forms.Padding get_Padding()
    * Void set_Padding(System.Windows.Forms.Padding)
    * Void add_PaddingChanged(System.EventHandler)
    * Void remove_PaddingChanged(System.EventHandler)
    * Void add_Paint(System.Windows.Forms.PaintEventHandler)
    * Void remove_Paint(System.Windows.Forms.PaintEventHandler)
    * Void add_QueryContinueDrag(System.Windows.Forms.QueryContinueDragEventHandler)
    * Void remove_QueryContinueDrag(System.Windows.Forms.QueryContinueDragEventHandler)
    * Void add_QueryAccessibilityHelp(System.Windows.Forms.QueryAccessibilityHelpEventHandler)
    * Void remove_QueryAccessibilityHelp(System.Windows.Forms.QueryAccessibilityHelpEventHandler)
    * Void add_DoubleClick(System.EventHandler)
    * Void remove_DoubleClick(System.EventHandler)
    * Void add_Enter(System.EventHandler)
    * Void remove_Enter(System.EventHandler)
    * Void add_GotFocus(System.EventHandler)
    * Void remove_GotFocus(System.EventHandler)
    * Void add_KeyDown(System.Windows.Forms.KeyEventHandler)
    * Void remove_KeyDown(System.Windows.Forms.KeyEventHandler)
    * Void add_KeyPress(System.Windows.Forms.KeyPressEventHandler)
    * Void remove_KeyPress(System.Windows.Forms.KeyPressEventHandler)
    * Void add_KeyUp(System.Windows.Forms.KeyEventHandler)
    * Void remove_KeyUp(System.Windows.Forms.KeyEventHandler)
    * Void add_Layout(System.Windows.Forms.LayoutEventHandler)
    * Void remove_Layout(System.Windows.Forms.LayoutEventHandler)
    * Void add_Leave(System.EventHandler)
    * Void remove_Leave(System.EventHandler)
    * Void add_LostFocus(System.EventHandler)
    * Void remove_LostFocus(System.EventHandler)
    * Void add_MouseClick(System.Windows.Forms.MouseEventHandler)
    * Void remove_MouseClick(System.Windows.Forms.MouseEventHandler)
    * Void add_MouseDoubleClick(System.Windows.Forms.MouseEventHandler)
    * Void remove_MouseDoubleClick(System.Windows.Forms.MouseEventHandler)
    * Void add_MouseCaptureChanged(System.EventHandler)
    * Void remove_MouseCaptureChanged(System.EventHandler)
    * Void add_MouseDown(System.Windows.Forms.MouseEventHandler)
    * Void remove_MouseDown(System.Windows.Forms.MouseEventHandler)
    * Void add_MouseEnter(System.EventHandler)
    * Void remove_MouseEnter(System.EventHandler)
    * Void add_MouseLeave(System.EventHandler)
    * Void remove_MouseLeave(System.EventHandler)
    * Void add_DpiChangedBeforeParent(System.EventHandler)
    * Void remove_DpiChangedBeforeParent(System.EventHandler)
    * Void add_DpiChangedAfterParent(System.EventHandler)
    * Void remove_DpiChangedAfterParent(System.EventHandler)
    * Void add_MouseHover(System.EventHandler)
    * Void remove_MouseHover(System.EventHandler)
    * Void add_MouseMove(System.Windows.Forms.MouseEventHandler)
    * Void remove_MouseMove(System.Windows.Forms.MouseEventHandler)
    * Void add_MouseUp(System.Windows.Forms.MouseEventHandler)
    * Void remove_MouseUp(System.Windows.Forms.MouseEventHandler)
    * Void add_MouseWheel(System.Windows.Forms.MouseEventHandler)
    * Void remove_MouseWheel(System.Windows.Forms.MouseEventHandler)
    * Void add_Move(System.EventHandler)
    * Void remove_Move(System.EventHandler)
    * Void add_PreviewKeyDown(System.Windows.Forms.PreviewKeyDownEventHandler)
    * Void remove_PreviewKeyDown(System.Windows.Forms.PreviewKeyDownEventHandler)
    * Void add_Resize(System.EventHandler)
    * Void remove_Resize(System.EventHandler)
    * Void add_ChangeUICues(System.Windows.Forms.UICuesEventHandler)
    * Void remove_ChangeUICues(System.Windows.Forms.UICuesEventHandler)
    * Void add_StyleChanged(System.EventHandler)
    * Void remove_StyleChanged(System.EventHandler)
    * Void add_SystemColorsChanged(System.EventHandler)
    * Void remove_SystemColorsChanged(System.EventHandler)
    * Void add_Validating(System.ComponentModel.CancelEventHandler)
    * Void remove_Validating(System.ComponentModel.CancelEventHandler)
    * Void add_Validated(System.EventHandler)
    * Void remove_Validated(System.EventHandler)
    * Void add_ParentChanged(System.EventHandler)
    * Void remove_ParentChanged(System.EventHandler)
    * System.IAsyncResult BeginInvoke(System.Delegate)
    * System.IAsyncResult BeginInvoke(System.Delegate, System.Object[])
    * Void BringToFront()
    * Boolean Contains(System.Windows.Forms.Control)
    * System.Drawing.Graphics CreateGraphics()
    * Void CreateControl()
    * System.Windows.Forms.DragDropEffects DoDragDrop(System.Object, System.Windows.Forms.DragDropEffects)
    * Void DrawToBitmap(System.Drawing.Bitmap, System.Drawing.Rectangle)
    * System.Object EndInvoke(System.IAsyncResult)
    * System.Windows.Forms.Form FindForm()
    * Boolean Focus()
    * System.Windows.Forms.Control GetChildAtPoint(System.Drawing.Point, System.Windows.Forms.GetChildAtPointSkip)
    * System.Windows.Forms.Control GetChildAtPoint(System.Drawing.Point)
    * System.Windows.Forms.IContainerControl GetContainerControl()
    * System.Windows.Forms.Control GetNextControl(System.Windows.Forms.Control, Boolean)
    * Void Hide()
    * Void Invalidate(System.Drawing.Region)
    * Void Invalidate(System.Drawing.Region, Boolean)
    * Void Invalidate()
    * Void Invalidate(Boolean)
    * Void Invalidate(System.Drawing.Rectangle)
    * Void Invalidate(System.Drawing.Rectangle, Boolean)
    * System.Object Invoke(System.Delegate)
    * System.Object Invoke(System.Delegate, System.Object[])
    * Int32 LogicalToDeviceUnits(Int32)
    * Void ScaleBitmapLogicalToDevice(System.Drawing.Bitmap ByRef)
    * Void PerformLayout()
    * Void PerformLayout(System.Windows.Forms.Control, System.String)
    * System.Drawing.Point PointToClient(System.Drawing.Point)
    * System.Drawing.Point PointToScreen(System.Drawing.Point)
    * Boolean PreProcessMessage(System.Windows.Forms.Message ByRef)
    * System.Windows.Forms.PreProcessControlState PreProcessControlMessage(System.Windows.Forms.Message ByRef)
    * Void ResetBackColor()
    * Void ResetCursor()
    * Void ResetFont()
    * Void ResetForeColor()
    * Void ResetRightToLeft()
    * System.Drawing.Rectangle RectangleToClient(System.Drawing.Rectangle)
    * System.Drawing.Rectangle RectangleToScreen(System.Drawing.Rectangle)
    * Void Refresh()
    * Void ResetText()
    * Void ResumeLayout()
    * Void ResumeLayout(Boolean)
    * Void Scale(Single)
    * Void Scale(Single, Single)
    * Void Scale(System.Drawing.SizeF)
    * Void Select()
    * Boolean SelectNextControl(System.Windows.Forms.Control, Boolean, Boolean, Boolean, Boolean)
    * Void SendToBack()
    * Void SetBounds(Int32, Int32, Int32, Int32)
    * Void SetBounds(Int32, Int32, Int32, Int32, System.Windows.Forms.BoundsSpecified)
    * Void Show()
    * Void SuspendLayout()
    * Void Update()
    * System.Windows.Forms.ImeMode get_ImeMode()
    * Void set_ImeMode(System.Windows.Forms.ImeMode)
    * Void add_ImeModeChanged(System.EventHandler)
    * Void remove_ImeModeChanged(System.EventHandler)
    * Void ResetImeMode()
    * Void add_Disposed(System.EventHandler)
    * Void remove_Disposed(System.EventHandler)
    * Void Dispose()
    * System.ComponentModel.IContainer get_Container()
    * System.Object GetLifetimeService()
    * System.Object InitializeLifetimeService()
    * System.Runtime.Remoting.ObjRef CreateObjRef(System.Type)
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets)
    * System.Windows.Forms.IButtonControl AcceptButton
    * System.Windows.Forms.Form ActiveMdiChild
    * Boolean AllowTransparency
    * Boolean AutoScale
    * System.Drawing.Size AutoScaleBaseSize
    * Boolean AutoScroll
    * Boolean AutoSize
    * System.Windows.Forms.AutoSizeMode AutoSizeMode
    * System.Windows.Forms.AutoValidate AutoValidate
    * System.Drawing.Color BackColor
    * System.Windows.Forms.FormBorderStyle FormBorderStyle
    * System.Windows.Forms.IButtonControl CancelButton
    * System.Drawing.Size ClientSize
    * Boolean ControlBox
    * System.Drawing.Rectangle DesktopBounds
    * System.Drawing.Point DesktopLocation
    * System.Windows.Forms.DialogResult DialogResult
    * Boolean HelpButton
    * System.Drawing.Icon Icon
    * Boolean IsMdiChild
    * Boolean IsMdiContainer
    * Boolean IsRestrictedWindow
    * Boolean KeyPreview
    * System.Drawing.Point Location
    * System.Drawing.Size MaximumSize
    * System.Windows.Forms.MenuStrip MainMenuStrip
    * System.Windows.Forms.Padding Margin
    * System.Windows.Forms.MainMenu Menu
    * System.Drawing.Size MinimumSize
    * Boolean MaximizeBox
    * System.Windows.Forms.Form[] MdiChildren
    * System.Windows.Forms.Form MdiParent
    * System.Windows.Forms.MainMenu MergedMenu
    * Boolean MinimizeBox
    * Boolean Modal
    * Double Opacity
    * System.Windows.Forms.Form[] OwnedForms
    * System.Windows.Forms.Form Owner
    * System.Drawing.Rectangle RestoreBounds
    * Boolean RightToLeftLayout
    * Boolean ShowInTaskbar
    * Boolean ShowIcon
    * System.Drawing.Size Size
    * System.Windows.Forms.SizeGripStyle SizeGripStyle
    * System.Windows.Forms.FormStartPosition StartPosition
    * Int32 TabIndex
    * Boolean TabStop
    * System.String Text
    * Boolean TopLevel
    * Boolean TopMost
    * System.Drawing.Color TransparencyKey
    * System.Windows.Forms.FormWindowState WindowState
    * System.Drawing.SizeF AutoScaleDimensions
    * System.Windows.Forms.AutoScaleMode AutoScaleMode
    * System.Windows.Forms.BindingContext BindingContext
    * System.Windows.Forms.Control ActiveControl
    * System.Drawing.SizeF CurrentAutoScaleDimensions
    * System.Windows.Forms.Form ParentForm
    * System.Drawing.Size AutoScrollMargin
    * System.Drawing.Point AutoScrollPosition
    * System.Drawing.Size AutoScrollMinSize
    * System.Drawing.Rectangle DisplayRectangle
    * System.Windows.Forms.HScrollProperties HorizontalScroll
    * System.Windows.Forms.VScrollProperties VerticalScroll
    * DockPaddingEdges DockPadding
    * System.Windows.Forms.AccessibleObject AccessibilityObject
    * System.String AccessibleDefaultActionDescription
    * System.String AccessibleDescription
    * System.String AccessibleName
    * System.Windows.Forms.AccessibleRole AccessibleRole
    * Boolean AllowDrop
    * System.Windows.Forms.AnchorStyles Anchor
    * System.Drawing.Point AutoScrollOffset
    * System.Windows.Forms.Layout.LayoutEngine LayoutEngine
    * System.Drawing.Image BackgroundImage
    * System.Windows.Forms.ImageLayout BackgroundImageLayout
    * Int32 Bottom
    * System.Drawing.Rectangle Bounds
    * Boolean CanFocus
    * Boolean CanSelect
    * Boolean Capture
    * Boolean CausesValidation
    * System.Drawing.Rectangle ClientRectangle
    * System.String CompanyName
    * Boolean ContainsFocus
    * System.Windows.Forms.ContextMenu ContextMenu
    * System.Windows.Forms.ContextMenuStrip ContextMenuStrip
    * ControlCollection Controls
    * Boolean Created
    * System.Windows.Forms.Cursor Cursor
    * System.Windows.Forms.ControlBindingsCollection DataBindings
    * Int32 DeviceDpi
    * Boolean IsDisposed
    * Boolean Disposing
    * System.Windows.Forms.DockStyle Dock
    * Boolean Enabled
    * Boolean Focused
    * System.Drawing.Font Font
    * System.Drawing.Color ForeColor
    * IntPtr Handle
    * Boolean HasChildren
    * Int32 Height
    * Boolean IsHandleCreated
    * Boolean InvokeRequired
    * Boolean IsAccessible
    * Boolean IsMirrored
    * Int32 Left
    * System.String Name
    * System.Windows.Forms.Control Parent
    * System.String ProductName
    * System.String ProductVersion
    * Boolean RecreatingHandle
    * System.Drawing.Region Region
    * Int32 Right
    * System.Windows.Forms.RightToLeft RightToLeft
    * System.ComponentModel.ISite Site
    * System.Object Tag
    * Int32 Top
    * System.Windows.Forms.Control TopLevelControl
    * Boolean UseWaitCursor
    * Boolean Visible
    * Int32 Width
    * System.Windows.Forms.IWindowTarget WindowTarget
    * System.Drawing.Size PreferredSize
    * System.Windows.Forms.Padding Padding
    * System.Windows.Forms.ImeMode ImeMode
    * System.ComponentModel.IContainer Container
    * System.EventHandler AutoSizeChanged
    * System.EventHandler AutoValidateChanged
    * System.ComponentModel.CancelEventHandler HelpButtonClicked
    * System.EventHandler MaximizedBoundsChanged
    * System.EventHandler MaximumSizeChanged
    * System.EventHandler MarginChanged
    * System.EventHandler MinimumSizeChanged
    * System.EventHandler TabIndexChanged
    * System.EventHandler TabStopChanged
    * System.EventHandler Activated
    * System.ComponentModel.CancelEventHandler Closing
    * System.EventHandler Closed
    * System.EventHandler Deactivate
    * System.Windows.Forms.FormClosingEventHandler FormClosing
    * System.Windows.Forms.FormClosedEventHandler FormClosed
    * System.EventHandler Load
    * System.EventHandler MdiChildActivate
    * System.EventHandler MenuComplete
    * System.EventHandler MenuStart
    * System.Windows.Forms.InputLanguageChangedEventHandler InputLanguageChanged
    * System.Windows.Forms.InputLanguageChangingEventHandler InputLanguageChanging
    * System.EventHandler RightToLeftLayoutChanged
    * System.EventHandler Shown
    * System.Windows.Forms.DpiChangedEventHandler DpiChanged
    * System.EventHandler ResizeBegin
    * System.EventHandler ResizeEnd
    * System.Windows.Forms.ScrollEventHandler Scroll
    * System.EventHandler BackColorChanged
    * System.EventHandler BackgroundImageChanged
    * System.EventHandler BackgroundImageLayoutChanged
    * System.EventHandler BindingContextChanged
    * System.EventHandler CausesValidationChanged
    * System.EventHandler ClientSizeChanged
    * System.EventHandler ContextMenuChanged
    * System.EventHandler ContextMenuStripChanged
    * System.EventHandler CursorChanged
    * System.EventHandler DockChanged
    * System.EventHandler EnabledChanged
    * System.EventHandler FontChanged
    * System.EventHandler ForeColorChanged
    * System.EventHandler LocationChanged
    * System.EventHandler RegionChanged
    * System.EventHandler RightToLeftChanged
    * System.EventHandler SizeChanged
    * System.EventHandler TextChanged
    * System.EventHandler VisibleChanged
    * System.EventHandler Click
    * System.Windows.Forms.ControlEventHandler ControlAdded
    * System.Windows.Forms.ControlEventHandler ControlRemoved
    * System.Windows.Forms.DragEventHandler DragDrop
    * System.Windows.Forms.DragEventHandler DragEnter
    * System.Windows.Forms.DragEventHandler DragOver
    * System.EventHandler DragLeave
    * System.Windows.Forms.GiveFeedbackEventHandler GiveFeedback
    * System.EventHandler HandleCreated
    * System.EventHandler HandleDestroyed
    * System.Windows.Forms.HelpEventHandler HelpRequested
    * System.Windows.Forms.InvalidateEventHandler Invalidated
    * System.EventHandler PaddingChanged
    * System.Windows.Forms.PaintEventHandler Paint
    * System.Windows.Forms.QueryContinueDragEventHandler QueryContinueDrag
    * System.Windows.Forms.QueryAccessibilityHelpEventHandler QueryAccessibilityHelp
    * System.EventHandler DoubleClick
    * System.EventHandler Enter
    * System.EventHandler GotFocus
    * System.Windows.Forms.KeyEventHandler KeyDown
    * System.Windows.Forms.KeyPressEventHandler KeyPress
    * System.Windows.Forms.KeyEventHandler KeyUp
    * System.Windows.Forms.LayoutEventHandler Layout
    * System.EventHandler Leave
    * System.EventHandler LostFocus
    * System.Windows.Forms.MouseEventHandler MouseClick
    * System.Windows.Forms.MouseEventHandler MouseDoubleClick
    * System.EventHandler MouseCaptureChanged
    * System.Windows.Forms.MouseEventHandler MouseDown
    * System.EventHandler MouseEnter
    * System.EventHandler MouseLeave
    * System.EventHandler DpiChangedBeforeParent
    * System.EventHandler DpiChangedAfterParent
    * System.EventHandler MouseHover
    * System.Windows.Forms.MouseEventHandler MouseMove
    * System.Windows.Forms.MouseEventHandler MouseUp
    * System.Windows.Forms.MouseEventHandler MouseWheel
    * System.EventHandler Move
    * System.Windows.Forms.PreviewKeyDownEventHandler PreviewKeyDown
    * System.EventHandler Resize
    * System.Windows.Forms.UICuesEventHandler ChangeUICues
    * System.EventHandler StyleChanged
    * System.EventHandler SystemColorsChanged
    * System.ComponentModel.CancelEventHandler Validating
    * System.EventHandler Validated
    * System.EventHandler ParentChanged
    * System.EventHandler ImeModeChanged
    * System.EventHandler Disposed
    * GMAssetCompiler.Form1+Prepare
# GMAssetCompiler.Form1+Prepare
  ## Members
    * Flobbster.Windows.Forms.PropertyBag Invoke(System.Object)
    * System.IAsyncResult BeginInvoke(System.Object, System.AsyncCallback, System.Object)
    * Flobbster.Windows.Forms.PropertyBag EndInvoke(System.IAsyncResult)
    * Void GetObjectData(System.Runtime.Serialization.SerializationInfo, System.Runtime.Serialization.StreamingContext)
    * Boolean Equals(System.Object)
    * System.Delegate[] GetInvocationList()
    * Int32 GetHashCode()
    * System.Object DynamicInvoke(System.Object[])
    * System.Reflection.MethodInfo get_Method()
    * System.Object get_Target()
    * System.Object Clone()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor(System.Object, IntPtr)
    * System.Reflection.MethodInfo Method
    * System.Object Target
# GMAssetCompiler.eObject
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.eObject OBJECT_SELF
    * GMAssetCompiler.eObject OBJECT_OTHER
    * GMAssetCompiler.eObject OBJECT_ALL
    * GMAssetCompiler.eObject OBJECT_NOONE
    * GMAssetCompiler.eObject OBJECT_GLOBAL
    * GMAssetCompiler.eObject OBJECT_LOCAL
    * GMAssetCompiler.eObject OBJECT_NOTSPECIFIED
# GMAssetCompiler.eAction
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.eAction ACT_NORMAL
    * GMAssetCompiler.eAction ACT_BEGIN
    * GMAssetCompiler.eAction ACT_END
    * GMAssetCompiler.eAction ACT_ELSE
    * GMAssetCompiler.eAction ACT_EXIT
    * GMAssetCompiler.eAction ACT_REPEAT
    * GMAssetCompiler.eAction ACT_VARIABLE
    * GMAssetCompiler.eAction ACT_CODE
# GMAssetCompiler.eExecuteTypes
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.eExecuteTypes EXE_NOTHING
    * GMAssetCompiler.eExecuteTypes EXE_FUNCTION
    * GMAssetCompiler.eExecuteTypes EXE_CODE
# GMAssetCompiler.eArgTypes
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.eArgTypes ARG_CONSTANT
    * GMAssetCompiler.eArgTypes ARG_EXPRESSION
    * GMAssetCompiler.eArgTypes ARG_STRING
    * GMAssetCompiler.eArgTypes ARG_STRINGEXP
    * GMAssetCompiler.eArgTypes ARG_BOOLEAN
    * GMAssetCompiler.eArgTypes ARG_MENU
    * GMAssetCompiler.eArgTypes ARG_SPRITE
    * GMAssetCompiler.eArgTypes ARG_SOUND
    * GMAssetCompiler.eArgTypes ARG_BACKGROUND
    * GMAssetCompiler.eArgTypes ARG_PATH
    * GMAssetCompiler.eArgTypes ARG_SCRIPT
    * GMAssetCompiler.eArgTypes ARG_OBJECT
    * GMAssetCompiler.eArgTypes ARG_ROOM
    * GMAssetCompiler.eArgTypes ARG_FONTR
    * GMAssetCompiler.eArgTypes ARG_COLOR
    * GMAssetCompiler.eArgTypes ARG_TIMELINE
    * GMAssetCompiler.eArgTypes ARG_FONT
# GMAssetCompiler.GMAction
  ## Members
    * Int32 get_LibID()
    * Int32 get_ID()
    * GMAssetCompiler.eAction get_Kind()
    * Boolean get_UseRelative()
    * Boolean get_IsQuestion()
    * Boolean get_UseApplyTo()
    * GMAssetCompiler.eExecuteTypes get_ExeType()
    * System.String get_Name()
    * System.String get_Code()
    * Void set_Code(System.String)
    * Int32 get_ArgumentCount()
    * System.Collections.Generic.IList`1[GMAssetCompiler.eArgTypes] get_ArgTypes()
    * Int32 get_Who()
    * Boolean get_Relative()
    * System.Collections.Generic.IList`1[System.String] get_Args()
    * Boolean get_IsNot()
    * Void ProcessFixups(GMAssetCompiler.GMAssets)
    * Void Compile(GMAssetCompiler.GMAssets)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.Xml.XmlNode)
    * Void .ctor(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void .ctor(GMAssetCompiler.GMAssets, System.IO.Stream)
    * Void .ctor(Int32, System.String)
    * Int32 LibID
    * Int32 ID
    * GMAssetCompiler.eAction Kind
    * Boolean UseRelative
    * Boolean IsQuestion
    * Boolean UseApplyTo
    * GMAssetCompiler.eExecuteTypes ExeType
    * System.String Name
    * System.String Code
    * Int32 ArgumentCount
    * System.Collections.Generic.IList`1[GMAssetCompiler.eArgTypes] ArgTypes
    * Int32 Who
    * Boolean Relative
    * System.Collections.Generic.IList`1[System.String] Args
    * Boolean IsNot
    * System.Collections.Generic.List`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMAction]] ms_ActionWhoFixups
# GMAssetCompiler.GMAssets
  ## Members
    * Void Decrypt(Int32, Byte[], Int64)
    * Void RemoveDND()
    * UInt32 ConvertToColour(System.Object)
    * System.String GetStatistics()
    * Int32 get_Magic()
    * Int32 get_Version()
    * Boolean get_Debug()
    * Void set_Debug(Boolean)
    * System.String get_Name()
    * Int32 get_GameID()
    * Void set_GameID(Int32)
    * System.Guid get_GameGUID()
    * Void set_GameGUID(System.Guid)
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMExtension] get_Extensions()
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMTrigger] get_Triggers()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMSound]] get_Sounds()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMSprite]] get_Sprites()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMBackground]] get_Backgrounds()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMPath]] get_Paths()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMScript]] get_Scripts()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMShader]] get_Shaders()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMFont]] get_Fonts()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMTimeLine]] get_TimeLines()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMObject]] get_Objects()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMRoom]] get_Rooms()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMDataFile]] get_DataFiles()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMAudioGroup]] get_AudioGroups()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMMacro]] get_Macros()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMSprite]] get_SpritesById()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMBackground]] get_BackgroundsById()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMObject]] get_ObjectsById()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMRoom]] get_RoomsById()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMMacro]] get_MacrosById()
    * System.Collections.Generic.Dictionary`2[System.Guid,GMAssetCompiler.GMResource] get_ResourcesById()
    * System.Collections.Generic.IList`1[System.Int32] get_RoomOrder()
    * System.Collections.Generic.IList`1[System.Guid] get_RoomOrderById()
    * System.Collections.Generic.IList`1[System.String] get_Libraries()
    * GMAssetCompiler.GMHelp get_Help()
    * Int32 get_RoomMaxId()
    * Int32 get_RoomMaxTileId()
    * System.String get_FileName()
    * Void set_FileName(System.String)
    * System.Collections.Generic.Dictionary`2[System.String,System.Collections.Generic.Dictionary`2[System.String,System.String]] get_Configs()
    * Void set_Configs(System.Collections.Generic.Dictionary`2[System.String,System.Collections.Generic.Dictionary`2[System.String,System.String]])
    * System.Collections.Generic.Dictionary`2[System.String,System.Collections.Generic.Dictionary`2[System.String,System.String]] get_ConfigConstants()
    * Void set_ConfigConstants(System.Collections.Generic.Dictionary`2[System.String,System.Collections.Generic.Dictionary`2[System.String,System.String]])
    * Int32 get_ConfigIndex()
    * Void set_ConfigIndex(Int32)
    * Int64 get_FunctionClassifications()
    * Void set_FunctionClassifications(Int64)
    * GMAssetCompiler.GMOptions get_Options()
    * Boolean get_DNDRemoved()
    * Void set_DNDRemoved(Boolean)
    * System.String ExpandFilename(System.String)
    * System.String GetProjectPath(System.String)
    * Void Extensions_Load(System.IO.Stream)
    * Void Trigger_Load(System.IO.Stream)
    * Void Constant_Load(System.IO.Stream)
    * Void Sound_Load(System.IO.Stream)
    * Void Sprite_Load(System.IO.Stream)
    * Void Background_Load(System.IO.Stream)
    * Void Path_Load(System.IO.Stream)
    * Void Script_Load(System.IO.Stream)
    * Void Font_Load(System.IO.Stream)
    * Void TimeLine_Load(System.IO.Stream)
    * Void Object_Load(System.IO.Stream)
    * Void Room_Load(System.IO.Stream)
    * Void DataFile_Load(System.IO.Stream)
    * Void Library_Load(System.IO.Stream)
    * Void Room_LoadOrder(System.IO.Stream)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Int32 Magic
    * Int32 Version
    * Boolean Debug
    * System.String Name
    * Int32 GameID
    * System.Guid GameGUID
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMExtension] Extensions
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMTrigger] Triggers
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMSound]] Sounds
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMSprite]] Sprites
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMBackground]] Backgrounds
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMPath]] Paths
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMScript]] Scripts
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMShader]] Shaders
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMFont]] Fonts
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMTimeLine]] TimeLines
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMObject]] Objects
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMRoom]] Rooms
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMDataFile]] DataFiles
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMAudioGroup]] AudioGroups
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMMacro]] Macros
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMSprite]] SpritesById
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMBackground]] BackgroundsById
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMObject]] ObjectsById
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMRoom]] RoomsById
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMMacro]] MacrosById
    * System.Collections.Generic.Dictionary`2[System.Guid,GMAssetCompiler.GMResource] ResourcesById
    * System.Collections.Generic.IList`1[System.Int32] RoomOrder
    * System.Collections.Generic.IList`1[System.Guid] RoomOrderById
    * System.Collections.Generic.IList`1[System.String] Libraries
    * GMAssetCompiler.GMHelp Help
    * Int32 RoomMaxId
    * Int32 RoomMaxTileId
    * System.String FileName
    * System.Collections.Generic.Dictionary`2[System.String,System.Collections.Generic.Dictionary`2[System.String,System.String]] Configs
    * System.Collections.Generic.Dictionary`2[System.String,System.Collections.Generic.Dictionary`2[System.String,System.String]] ConfigConstants
    * Int32 ConfigIndex
    * Int64 FunctionClassifications
    * GMAssetCompiler.GMOptions Options
    * Boolean DNDRemoved
    * GMAssetCompiler.GMAssets+eGMXType
    * GMAssetCompiler.GMAssets+SGMXLoadInfo
# GMAssetCompiler.GMAssets+eGMXType
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * eGMXType Extension
    * eGMXType Sounds
    * eGMXType Sprites
    * eGMXType Backgrounds
    * eGMXType Paths
    * eGMXType Scripts
    * eGMXType Shaders
    * eGMXType Fonts
    * eGMXType Timelines
    * eGMXType Objects
    * eGMXType Rooms
    * eGMXType Datafiles
# GMAssetCompiler.GMAssets+SGMXLoadInfo
  ## Members
    * eGMXType get_Type()
    * Void set_Type(eGMXType)
    * System.String get_Name()
    * Void set_Name(System.String)
    * System.String get_FileName()
    * Void set_FileName(System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(eGMXType, System.String, System.String)
    * eGMXType Type
    * System.String Name
    * System.String FileName
# GMAssetCompiler.GMAssets+Factory`1[T]
  ## Members
    * T Invoke(GMAssetCompiler.GMAssets, System.IO.Stream)
    * System.IAsyncResult BeginInvoke(GMAssetCompiler.GMAssets, System.IO.Stream, System.AsyncCallback, System.Object)
    * T EndInvoke(System.IAsyncResult)
    * Void GetObjectData(System.Runtime.Serialization.SerializationInfo, System.Runtime.Serialization.StreamingContext)
    * Boolean Equals(System.Object)
    * System.Delegate[] GetInvocationList()
    * Int32 GetHashCode()
    * System.Object DynamicInvoke(System.Object[])
    * System.Reflection.MethodInfo get_Method()
    * System.Object get_Target()
    * System.Object Clone()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor(System.Object, IntPtr)
    * System.Reflection.MethodInfo Method
    * System.Object Target
# GMAssetCompiler.GMBackground
  ## Members
    * Boolean get_Transparent()
    * Boolean get_Smooth()
    * Boolean get_Preload()
    * Boolean get_Tileset()
    * Void set_Tileset(Boolean)
    * GMAssetCompiler.GMBitmap32 get_Bitmap()
    * Int32 get_Width()
    * Int32 get_Height()
    * Boolean get_HTile()
    * Boolean get_VTile()
    * Int32 get_Columns()
    * Int32 get_SpriteIndex()
    * Int32 get_TileWidth()
    * Int32 get_TileHeight()
    * Int32 get_TileXOff()
    * Int32 get_TileYOff()
    * Int32 get_TileHSep()
    * Int32 get_TileVSep()
    * System.Collections.Generic.List`1[System.Int32] get_TextureGroups()
    * Boolean get_For3D()
    * System.String get_BitmapFileName()
    * System.String get_SourceFileName()
    * Void SetFromJson(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * System.String get_Name()
    * System.Guid get_GUID()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.String)
    * Void .ctor(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void .ctor(GMAssetCompiler.GMAssets, GMAssetCompiler.GMSprite)
    * Void .ctor(GMAssetCompiler.GMAssets, System.IO.Stream)
    * Boolean Transparent
    * Boolean Smooth
    * Boolean Preload
    * Boolean Tileset
    * GMAssetCompiler.GMBitmap32 Bitmap
    * Int32 Width
    * Int32 Height
    * Boolean HTile
    * Boolean VTile
    * Int32 Columns
    * Int32 SpriteIndex
    * Int32 TileWidth
    * Int32 TileHeight
    * Int32 TileXOff
    * Int32 TileYOff
    * Int32 TileHSep
    * Int32 TileVSep
    * System.Collections.Generic.List`1[System.Int32] TextureGroups
    * Boolean For3D
    * System.String BitmapFileName
    * System.String SourceFileName
    * System.String Name
    * System.Guid GUID
# GMAssetCompiler.GMBitmap32
  ## Members
    * Int32 get_Width()
    * Int32 get_Height()
    * Byte[] get_Data()
    * Void SetAlphaFromBitmap(GMAssetCompiler.GMBitmap32)
    * System.Drawing.Bitmap get_Bitmap()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String)
    * Void .ctor(System.IO.Stream)
    * Int32 Width
    * Int32 Height
    * Byte[] Data
    * System.Drawing.Bitmap Bitmap
# GMAssetCompiler.GMDataFile
  ## Members
    * System.String get_FileName()
    * System.String get_OrigName()
    * Boolean get_Exists()
    * Int32 get_Size()
    * Boolean get_Store()
    * Byte[] get_Data()
    * Int32 get_ExportAction()
    * System.String get_ExportDir()
    * Boolean get_Overwrite()
    * Boolean get_FreeData()
    * Boolean get_RemoveEnd()
    * System.Collections.Generic.Dictionary`2[System.String,System.Int64] get_ConfigOptions()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.Xml.XmlNode, System.String)
    * Void .ctor(System.String, System.String)
    * Void .ctor(GMAssetCompiler.GMAssets, System.IO.Stream)
    * System.String FileName
    * System.String OrigName
    * Boolean Exists
    * Int32 Size
    * Boolean Store
    * Byte[] Data
    * Int32 ExportAction
    * System.String ExportDir
    * Boolean Overwrite
    * Boolean FreeData
    * Boolean RemoveEnd
    * System.Collections.Generic.Dictionary`2[System.String,System.Int64] ConfigOptions
# GMAssetCompiler.GMEvent
  ## Members
    * Int32 get_CompiledIndex()
    * Void set_CompiledIndex(Int32)
    * System.Collections.Generic.List`1[GMAssetCompiler.GMAction] get_Actions()
    * Void set_Actions(System.Collections.Generic.List`1[GMAssetCompiler.GMAction])
    * Int32 get_EventNum()
    * Int32 get_EventType()
    * System.String get_EventName()
    * System.String CompressEvent(System.String, System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.Xml.XmlNode)
    * Void .ctor(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void .ctor(GMAssetCompiler.GMAssets, System.IO.Stream)
    * Int32 CompiledIndex
    * System.Collections.Generic.List`1[GMAssetCompiler.GMAction] Actions
    * Int32 EventNum
    * Int32 EventType
    * System.String EventName
# GMAssetCompiler.FrameworkInfo
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Boolean WeakReference
    * System.String Name
# GMAssetCompiler.GMExtension
  ## Members
    * System.String get_Name()
    * System.String get_Folder()
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMExtensionInclude] get_Includes()
    * System.Collections.Generic.IList`1[System.Byte[]] get_ExtensionDLL()
    * Boolean get_Used()
    * Void set_Used(Boolean)
    * System.String get_Version()
    * Void set_Version(System.String)
    * System.String get_Author()
    * Void set_Author(System.String)
    * System.String get_Date()
    * Void set_Date(System.String)
    * System.String get_License()
    * Void set_License(System.String)
    * System.String get_Description()
    * Void set_Description(System.String)
    * System.String get_HelpFile()
    * Void set_HelpFile(System.String)
    * System.String get_InstallDir()
    * Void set_InstallDir(System.String)
    * System.String get_ClassName()
    * Void set_ClassName(System.String)
    * System.String get_AndroidClassName()
    * Void set_AndroidClassName(System.String)
    * System.String get_SourceDir()
    * Void set_SourceDir(System.String)
    * System.String get_MacSourceDir()
    * Void set_MacSourceDir(System.String)
    * System.String get_MacLinkerFlags()
    * Void set_MacLinkerFlags(System.String)
    * System.String get_MacCompilerFlags()
    * Void set_MacCompilerFlags(System.String)
    * System.String get_ProductID()
    * Void set_ProductID(System.String)
    * System.String get_PackageID()
    * Void set_PackageID(System.String)
    * System.Collections.Generic.IList`1[GMAssetCompiler.FrameworkInfo] get_iosSystemFrameworks()
    * System.Collections.Generic.IList`1[GMAssetCompiler.FrameworkInfo] get_iosThirdPartyFrameworks()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.String)
    * Void .ctor(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void .ctor(GMAssetCompiler.GMAssets, System.IO.Stream)
    * System.String Name
    * System.String Folder
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMExtensionInclude] Includes
    * System.Collections.Generic.IList`1[System.Byte[]] ExtensionDLL
    * Boolean Used
    * System.String Version
    * System.String Author
    * System.String Date
    * System.String License
    * System.String Description
    * System.String HelpFile
    * System.String InstallDir
    * System.String ClassName
    * System.String AndroidClassName
    * System.String SourceDir
    * System.String MacSourceDir
    * System.String MacLinkerFlags
    * System.String MacCompilerFlags
    * System.String ProductID
    * System.String PackageID
    * System.Collections.Generic.IList`1[GMAssetCompiler.FrameworkInfo] iosSystemFrameworks
    * System.Collections.Generic.IList`1[GMAssetCompiler.FrameworkInfo] iosThirdPartyFrameworks
# GMAssetCompiler.GMExtensionConstant
  ## Members
    * System.String get_Name()
    * System.String get_Value()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.Xml.XmlNode)
    * Void .ctor(GMAssetCompiler.GMAssets, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void .ctor(System.IO.Stream)
    * System.String Name
    * System.String Value
# GMAssetCompiler.GMExtensionFunction
  ## Members
    * System.String get_Name()
    * System.String get_ExtName()
    * Int32 get_Kind()
    * Int32 get_Id()
    * System.Collections.Generic.IList`1[System.Int32] get_Args()
    * Int32 get_ArgCount()
    * Int32 get_ReturnType()
    * System.String get_Help()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.Xml.XmlNode)
    * Void .ctor(GMAssetCompiler.GMAssets, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void .ctor(System.IO.Stream)
    * System.String Name
    * System.String ExtName
    * Int32 Kind
    * Int32 Id
    * System.Collections.Generic.IList`1[System.Int32] Args
    * Int32 ArgCount
    * Int32 ReturnType
    * System.String Help
    * GMAssetCompiler.GMExtensionFunction+eReturnType
# GMAssetCompiler.GMExtensionFunction+eReturnType
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * eReturnType eString
    * eReturnType eReal
# GMAssetCompiler.ExtensionKind
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.ExtensionKind Error
    * GMAssetCompiler.ExtensionKind Undefined
    * GMAssetCompiler.ExtensionKind Dll
    * GMAssetCompiler.ExtensionKind Gml
    * GMAssetCompiler.ExtensionKind Lib
    * GMAssetCompiler.ExtensionKind Other
    * GMAssetCompiler.ExtensionKind Stdcall
    * GMAssetCompiler.ExtensionKind Cdecl
# GMAssetCompiler.GMExtensionInclude
  ## Members
    * System.String get_Filename()
    * System.String get_NewFilename()
    * Void set_NewFilename(System.String)
    * Int32 get_Kind()
    * System.String get_Init()
    * System.String get_Final()
    * Boolean get_Uncompress()
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMExtensionFunction] get_Functions()
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMExtensionConstant] get_Constants()
    * System.Collections.Generic.Dictionary`2[System.String,System.Int64] get_ConfigOptions()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,System.Int64]] get_ProxyFiles()
    * Boolean get_Used()
    * Void set_Used(Boolean)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.Xml.XmlNode)
    * Void .ctor(GMAssetCompiler.GMAssets, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void .ctor(System.IO.Stream)
    * System.String Filename
    * System.String NewFilename
    * Int32 Kind
    * System.String Init
    * System.String Final
    * Boolean Uncompress
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMExtensionFunction] Functions
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMExtensionConstant] Constants
    * System.Collections.Generic.Dictionary`2[System.String,System.Int64] ConfigOptions
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,System.Int64]] ProxyFiles
    * Boolean Used
# GMAssetCompiler.GMKerning
  ## Members
    * Int32 get_Other()
    * Void set_Other(Int32)
    * Int32 get_Amount()
    * Void set_Amount(Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 Other
    * Int32 Amount
# GMAssetCompiler.GMGlyph
  ## Members
    * Int32 get_X()
    * Void set_X(Int32)
    * Int32 get_Y()
    * Void set_Y(Int32)
    * Int32 get_W()
    * Void set_W(Int32)
    * Int32 get_H()
    * Void set_H(Int32)
    * Int32 get_Shift()
    * Void set_Shift(Int32)
    * Int32 get_Offset()
    * Void set_Offset(Int32)
    * System.Collections.Generic.List`1[GMAssetCompiler.GMKerning] get_Kerning()
    * Void set_Kerning(System.Collections.Generic.List`1[GMAssetCompiler.GMKerning])
    * Int32 get_Char()
    * Void set_Char(Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(Int32, Int32, Int32, Int32, Int32, Int32, Int32, System.Collections.Generic.List`1[GMAssetCompiler.GMKerning])
    * Int32 X
    * Int32 Y
    * Int32 W
    * Int32 H
    * Int32 Shift
    * Int32 Offset
    * System.Collections.Generic.List`1[GMAssetCompiler.GMKerning] Kerning
    * Int32 Char
# GMAssetCompiler.GMFont
  ## Members
    * System.String get_AssetName()
    * Int32 get_Size()
    * Boolean get_Bold()
    * Boolean get_Italic()
    * Int32 get_First()
    * Int32 get_Last()
    * Int32 get_CharSet()
    * Int32 get_AntiAlias()
    * System.Collections.Generic.List`1[GMAssetCompiler.GMGlyph] get_Glyphs()
    * System.Drawing.Bitmap get_Bitmap()
    * System.String get_BitmapFileName()
    * System.Collections.Generic.List`1[System.Int32] get_TextureGroups()
    * System.Collections.Generic.List`1[System.Collections.Generic.KeyValuePair`2[System.Int32,System.Int32]] get_Ranges()
    * System.String get_SourceFileName()
    * Void SetFromJson(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void UpdateBitmapFile(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.List`1[System.String])
    * System.String get_Name()
    * System.Guid get_GUID()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.String)
    * Void .ctor(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void .ctor(GMAssetCompiler.GMAssets, System.IO.Stream)
    * System.String AssetName
    * Int32 Size
    * Boolean Bold
    * Boolean Italic
    * Int32 First
    * Int32 Last
    * Int32 CharSet
    * Int32 AntiAlias
    * System.Collections.Generic.List`1[GMAssetCompiler.GMGlyph] Glyphs
    * System.Drawing.Bitmap Bitmap
    * System.String BitmapFileName
    * System.Collections.Generic.List`1[System.Int32] TextureGroups
    * System.Collections.Generic.List`1[System.Collections.Generic.KeyValuePair`2[System.Int32,System.Int32]] Ranges
    * System.String SourceFileName
    * System.String Name
    * System.Guid GUID
    * System.String ResourceTreePath
# GMAssetCompiler.GMHelp
  ## Members
    * Int32 get_BackgroundColour()
    * Boolean get_Mimic()
    * System.String get_Caption()
    * Int32 get_Left()
    * Int32 get_Top()
    * Int32 get_Width()
    * Int32 get_Height()
    * Boolean get_Border()
    * Boolean get_Sizable()
    * Boolean get_OnTop()
    * Boolean get_Modal()
    * System.String get_Text()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.Xml.XmlNode)
    * Void .ctor(GMAssetCompiler.GMAssets, System.IO.Stream)
    * Int32 BackgroundColour
    * Boolean Mimic
    * System.String Caption
    * Int32 Left
    * Int32 Top
    * Int32 Width
    * Int32 Height
    * Boolean Border
    * Boolean Sizable
    * Boolean OnTop
    * Boolean Modal
    * System.String Text
# GMAssetCompiler.GMPhysicsShapeVertex
  ## Members
    * Single get_X()
    * Void set_X(Single)
    * Single get_Y()
    * Void set_Y(Single)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Single X
    * Single Y
# GMAssetCompiler.SubTypeAndEvent
  ## Members
    * Int32 get_SubType()
    * Void set_SubType(Int32)
    * GMAssetCompiler.GMEvent get_Event()
    * Void set_Event(GMAssetCompiler.GMEvent)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(Int32, GMAssetCompiler.GMEvent)
    * Int32 SubType
    * GMAssetCompiler.GMEvent Event
# GMAssetCompiler.GMObject
  ## Members
    * System.Guid get_ParentGUID()
    * Void set_ParentGUID(System.Guid)
    * Int32 get_SpriteIndex()
    * Boolean get_Solid()
    * Boolean get_Visible()
    * Int32 get_Depth()
    * Boolean get_Persistent()
    * Int32 get_Parent()
    * Int32 get_Mask()
    * System.Collections.Generic.IList`1[System.Collections.Generic.IList`1[GMAssetCompiler.SubTypeAndEvent]] get_Events()
    * Boolean get_PhysicsObject()
    * Boolean get_PhysicsObjectSensor()
    * Int32 get_PhysicsObjectShape()
    * Single get_PhysicsObjectDensity()
    * Single get_PhysicsObjectRestitution()
    * Int32 get_PhysicsObjectGroup()
    * Single get_PhysicsObjectLinearDamping()
    * Single get_PhysicsObjectAngularDamping()
    * Single get_PhysicsObjectFriction()
    * Boolean get_PhysicsObjectAwake()
    * Boolean get_PhysicsObjectKinematic()
    * System.Collections.Generic.List`1[GMAssetCompiler.GMPhysicsShapeVertex] get_PhysicsShapeVertices()
    * System.String get_ParentName()
    * Void set_ParentName(System.String)
    * System.String get_SourceFileName()
    * Void ProcessFixups(GMAssetCompiler.GMAssets)
    * Int32 GMX_FindObject(System.String, System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMObject]])
    * System.Collections.Generic.IList`1[System.Collections.Generic.IList`1[GMAssetCompiler.SubTypeAndEvent]] CreateEvents(GMAssetCompiler.GMAssets, System.Xml.XmlNode)
    * Void SetFromJson(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void UpdateEventCode(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.List`1[System.String])
    * System.String GetEventName_Simple(Int32, Int32, System.String)
    * System.String get_Name()
    * System.Guid get_GUID()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.String)
    * Void .ctor(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void .ctor(GMAssetCompiler.GMAssets, System.IO.Stream)
    * System.Guid ParentGUID
    * Int32 SpriteIndex
    * Boolean Solid
    * Boolean Visible
    * Int32 Depth
    * Boolean Persistent
    * Int32 Parent
    * Int32 Mask
    * System.Collections.Generic.IList`1[System.Collections.Generic.IList`1[GMAssetCompiler.SubTypeAndEvent]] Events
    * Boolean PhysicsObject
    * Boolean PhysicsObjectSensor
    * Int32 PhysicsObjectShape
    * Single PhysicsObjectDensity
    * Single PhysicsObjectRestitution
    * Int32 PhysicsObjectGroup
    * Single PhysicsObjectLinearDamping
    * Single PhysicsObjectAngularDamping
    * Single PhysicsObjectFriction
    * Boolean PhysicsObjectAwake
    * Boolean PhysicsObjectKinematic
    * System.Collections.Generic.List`1[GMAssetCompiler.GMPhysicsShapeVertex] PhysicsShapeVertices
    * System.String ParentName
    * System.String SourceFileName
    * System.String Name
    * System.Guid GUID
    * System.String ResourceTreePath
# GMAssetCompiler.GMOptions
  ## Members
    * System.String get_VersionBuild()
    * Void set_VersionBuild(System.String)
    * System.String get_VersionRevision()
    * Void set_VersionRevision(System.String)
    * System.Collections.Generic.List`1[GMAssetCompiler.GMTextureGroup] get_TextureGroups()
    * Void SetFromConfig(System.Collections.Generic.Dictionary`2[System.String,System.String], System.String)
    * Void SetFromJson(System.Collections.Generic.Dictionary`2[System.String,System.Object], System.String)
    * Void UpdateFromConfigDelta(System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Boolean get_DebugEnabled()
    * System.String get_Config()
    * Boolean get_UseNewAudio()
    * Boolean get_UseFastCollision()
    * Boolean get_OutputDebugToConsole()
    * System.String get_html5jsprepend()
    * System.String get_html5outputfile()
    * Int32 get_StudioEdition()
    * Void set_StudioEdition(Int32)
    * System.String get_DisplayName()
    * Void set_DisplayName(System.String)
    * Int64 get_ActiveTargets()
    * Boolean get_FullScreen()
    * Boolean get_InterpolatePixels()
    * Boolean get_NoBorder()
    * Boolean get_ShowCursor()
    * Int32 get_Scale()
    * Boolean get_Sizeable()
    * Boolean get_StayOnTop()
    * Int32 get_WindowColour()
    * Boolean get_ChangeResolution()
    * Int32 get_ColorDepth()
    * Int32 get_Resolution()
    * Int32 get_Frequency()
    * Boolean get_NoButtons()
    * Int32 get_Sync_Vertex()
    * Boolean get_NoScreenSaver()
    * Boolean get_ScreenKey()
    * Boolean get_UseFrontTouch()
    * Boolean get_UseRearTouch()
    * Boolean get_Borderless()
    * Boolean get_HelpKey()
    * Boolean get_QuitKey()
    * Boolean get_SaveKey()
    * Boolean get_ScreenShotKey()
    * Boolean get_CloseSec()
    * Int32 get_Priority()
    * Boolean get_Freeze()
    * Boolean get_ShowProgress()
    * System.Drawing.Bitmap get_BackImage()
    * System.Drawing.Bitmap get_FrontImage()
    * System.Drawing.Bitmap get_LoadImage()
    * Boolean get_LoadTransparent()
    * Int32 get_LoadAlpha()
    * Boolean get_ScaleProgress()
    * Boolean get_DisplayErrors()
    * Boolean get_WriteErrors()
    * Boolean get_AbortErrors()
    * Boolean get_VariableErrors()
    * Int32 get_WebGL()
    * Boolean get_CreationEventOrder()
    * System.String get_Html5BrowserTitle()
    * Boolean get_Html5UseParticles()
    * Boolean get_Html5LocalRunAlert()
    * System.Collections.Generic.Dictionary`2[System.String,System.String] get_Constants()
    * Void set_Constants(System.Collections.Generic.Dictionary`2[System.String,System.String])
    * Boolean get_SpotifyApp()
    * Void set_SpotifyApp(Boolean)
    * Boolean get_GoogleAnalytics()
    * Void set_GoogleAnalytics(Boolean)
    * System.String get_GAWebPropertyID()
    * Void set_GAWebPropertyID(System.String)
    * Boolean get_FlurryAnalytics()
    * Void set_FlurryAnalytics(Boolean)
    * System.String get_FlurryAPIKey()
    * Void set_FlurryAPIKey(System.String)
    * Int32 get_SaveLocation()
    * Void set_SaveLocation(Int32)
    * System.String get_Win8AdvertisingId()
    * Void set_Win8AdvertisingId(System.String)
    * System.Collections.Generic.List`1[System.String] get_Win8AdUnitIds()
    * Void set_Win8AdUnitIds(System.Collections.Generic.List`1[System.String])
    * System.String get_Win8AnalyticsId()
    * Void set_Win8AnalyticsId(System.String)
    * System.String get_VersionMajor()
    * Void set_VersionMajor(System.String)
    * System.String get_VersionMinor()
    * Void set_VersionMinor(System.String)
    * System.String get_Name()
    * System.Guid get_GUID()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Boolean DebugEnabled
    * System.String Config
    * Boolean UseNewAudio
    * Boolean UseFastCollision
    * Boolean OutputDebugToConsole
    * System.String html5jsprepend
    * System.String html5outputfile
    * Int32 StudioEdition
    * System.String DisplayName
    * Int64 ActiveTargets
    * Boolean FullScreen
    * Boolean InterpolatePixels
    * Boolean NoBorder
    * Boolean ShowCursor
    * Int32 Scale
    * Boolean Sizeable
    * Boolean StayOnTop
    * Int32 WindowColour
    * Boolean ChangeResolution
    * Int32 ColorDepth
    * Int32 Resolution
    * Int32 Frequency
    * Boolean NoButtons
    * Int32 Sync_Vertex
    * Boolean NoScreenSaver
    * Boolean ScreenKey
    * Boolean UseFrontTouch
    * Boolean UseRearTouch
    * Boolean Borderless
    * Boolean HelpKey
    * Boolean QuitKey
    * Boolean SaveKey
    * Boolean ScreenShotKey
    * Boolean CloseSec
    * Int32 Priority
    * Boolean Freeze
    * Boolean ShowProgress
    * System.Drawing.Bitmap BackImage
    * System.Drawing.Bitmap FrontImage
    * System.Drawing.Bitmap LoadImage
    * Boolean LoadTransparent
    * Int32 LoadAlpha
    * Boolean ScaleProgress
    * Boolean DisplayErrors
    * Boolean WriteErrors
    * Boolean AbortErrors
    * Boolean VariableErrors
    * Int32 WebGL
    * Boolean CreationEventOrder
    * System.String Html5BrowserTitle
    * Boolean Html5UseParticles
    * Boolean Html5LocalRunAlert
    * System.Collections.Generic.Dictionary`2[System.String,System.String] Constants
    * Boolean SpotifyApp
    * Boolean GoogleAnalytics
    * System.String GAWebPropertyID
    * Boolean FlurryAnalytics
    * System.String FlurryAPIKey
    * Int32 SaveLocation
    * System.String Win8AdvertisingId
    * System.Collections.Generic.List`1[System.String] Win8AdUnitIds
    * System.String Win8AnalyticsId
    * System.String VersionMajor
    * System.String VersionMinor
    * System.String VersionBuild
    * System.String VersionRevision
    * System.Collections.Generic.List`1[GMAssetCompiler.GMTextureGroup] TextureGroups
    * System.String Name
    * System.Guid GUID
# GMAssetCompiler.GMPathPoint
  ## Members
    * Double get_X()
    * Double get_Y()
    * Double get_Speed()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(Double, Double, Double)
    * Double X
    * Double Y
    * Double Speed
# GMAssetCompiler.GMPath
  ## Members
    * Int32 get_Kind()
    * Boolean get_Closed()
    * Int32 get_Precision()
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMPathPoint] get_Points()
    * Int32 get_BackRoom()
    * Boolean get_HSnap()
    * Boolean get_VSnap()
    * Void SetFromJson(System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * System.String get_Name()
    * System.Guid get_GUID()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.String)
    * Void .ctor(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void .ctor(GMAssetCompiler.GMAssets, System.IO.Stream)
    * Int32 Kind
    * Boolean Closed
    * Int32 Precision
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMPathPoint] Points
    * Int32 BackRoom
    * Boolean HSnap
    * Boolean VSnap
    * System.String Name
    * System.Guid GUID
# GMAssetCompiler.GMBack
  ## Members
    * Boolean get_Visible()
    * Boolean get_Foreground()
    * Int32 get_Index()
    * Int32 get_X()
    * Int32 get_Y()
    * Boolean get_HTiled()
    * Boolean get_VTiled()
    * Int32 get_HSpeed()
    * Int32 get_VSpeed()
    * Double get_XScale()
    * Double get_YScale()
    * Int32 get_Blend()
    * Double get_Alpha()
    * Boolean get_Stretch()
    * Double get_FirstFrame()
    * Double get_FrameSpeed()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.Xml.XmlNode)
    * Void .ctor(GMAssetCompiler.GMAssets, System.Collections.Generic.Dictionary`2[System.String,System.Object], Boolean)
    * Void .ctor(System.IO.Stream)
    * Boolean Visible
    * Boolean Foreground
    * Int32 Index
    * Int32 X
    * Int32 Y
    * Boolean HTiled
    * Boolean VTiled
    * Int32 HSpeed
    * Int32 VSpeed
    * Double XScale
    * Double YScale
    * Int32 Blend
    * Double Alpha
    * Boolean Stretch
    * Double FirstFrame
    * Double FrameSpeed
# GMAssetCompiler.GMView
  ## Members
    * Boolean get_Visible()
    * Int32 get_XView()
    * Int32 get_YView()
    * Int32 get_WView()
    * Int32 get_HView()
    * Int32 get_XPort()
    * Int32 get_YPort()
    * Int32 get_WPort()
    * Int32 get_HPort()
    * Double get_Angle()
    * Int32 get_HBorder()
    * Int32 get_VBorder()
    * Int32 get_HSpeed()
    * Int32 get_VSpeed()
    * Int32 get_Index()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.Xml.XmlNode)
    * Void .ctor(GMAssetCompiler.GMAssets, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void .ctor(System.IO.Stream)
    * Boolean Visible
    * Int32 XView
    * Int32 YView
    * Int32 WView
    * Int32 HView
    * Int32 XPort
    * Int32 YPort
    * Int32 WPort
    * Int32 HPort
    * Double Angle
    * Int32 HBorder
    * Int32 VBorder
    * Int32 HSpeed
    * Int32 VSpeed
    * Int32 Index
# GMAssetCompiler.GMTile
  ## Members
    * Int32 get_X()
    * Int32 get_Y()
    * Int32 get_Index()
    * Int32 get_XO()
    * Int32 get_YO()
    * Int32 get_W()
    * Int32 get_H()
    * Int32 get_Depth()
    * Int32 get_Id()
    * Double get_XScale()
    * Double get_YScale()
    * Int32 get_Blend()
    * Double get_Alpha()
    * Boolean get_Visible()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.Xml.XmlNode, Int32)
    * Void .ctor(GMAssetCompiler.GMAssets, System.Collections.Generic.Dictionary`2[System.String,System.Object], Int32, Int32)
    * Void .ctor(Int32, Int32, Int32, Int32, Int32, Int32, Int32, Int32, Int32, Boolean, Boolean, Boolean)
    * Void .ctor(System.IO.Stream, Int32)
    * Int32 X
    * Int32 Y
    * Int32 Index
    * Int32 XO
    * Int32 YO
    * Int32 W
    * Int32 H
    * Int32 Depth
    * Int32 Id
    * Double XScale
    * Double YScale
    * Int32 Blend
    * Double Alpha
    * Boolean Visible
# GMAssetCompiler.GMSpriteGraphic
  ## Members
    * System.String get_Name()
    * Int32 get_Index()
    * Int32 get_X()
    * Int32 get_Y()
    * Double get_XScale()
    * Double get_YScale()
    * Int32 get_Blend()
    * Double get_Alpha()
    * Single get_AnimationSpeed()
    * Single get_FrameIndex()
    * Single get_Rotation()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * System.String Name
    * Int32 Index
    * Int32 X
    * Int32 Y
    * Double XScale
    * Double YScale
    * Int32 Blend
    * Double Alpha
    * Single AnimationSpeed
    * Single FrameIndex
    * Single Rotation
# GMAssetCompiler.GMInstance
  ## Members
    * System.Guid get_ParentGUID()
    * Boolean get_InheritCode()
    * Int32 get_X()
    * Int32 get_Y()
    * Int32 get_Id()
    * Int32 get_Index()
    * System.String get_Code()
    * Void set_Code(System.String)
    * Double get_ScaleX()
    * Double get_ScaleY()
    * UInt32 get_Colour()
    * Double get_Rotation()
    * Int32 get_CompiledIndex()
    * Void set_CompiledIndex(Int32)
    * Void ProcessFixups()
    * System.String get_Name()
    * System.Guid get_GUID()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.Xml.XmlNode, Int32)
    * Void .ctor(GMAssetCompiler.GMAssets, System.Collections.Generic.Dictionary`2[System.String,System.Object], Int32, System.String)
    * Void .ctor(System.IO.Stream, Int32)
    * Void .ctor(System.IO.Stream, Boolean)
    * System.Guid ParentGUID
    * Boolean InheritCode
    * Int32 X
    * Int32 Y
    * Int32 Id
    * Int32 Index
    * System.String Code
    * Double ScaleX
    * Double ScaleY
    * UInt32 Colour
    * Double Rotation
    * Int32 CompiledIndex
    * System.String Name
    * System.Guid GUID
    * System.Collections.Generic.Dictionary`2[System.Guid,GMAssetCompiler.GMInstance] AllInstances
# GMAssetCompiler.GMRoomMakerSettings
  ## Members
    * Boolean get_IsSet()
    * Void set_IsSet(Boolean)
    * Int32 get_Width()
    * Void set_Width(Int32)
    * Int32 get_Height()
    * Void set_Height(Int32)
    * Boolean get_ShowGrid()
    * Void set_ShowGrid(Boolean)
    * Boolean get_ShowObjects()
    * Void set_ShowObjects(Boolean)
    * Boolean get_ShowTiles()
    * Void set_ShowTiles(Boolean)
    * Boolean get_ShowBackgrounds()
    * Void set_ShowBackgrounds(Boolean)
    * Boolean get_ShowForegrounds()
    * Void set_ShowForegrounds(Boolean)
    * Boolean get_ShowViews()
    * Void set_ShowViews(Boolean)
    * Boolean get_DeleteUnderlyingObj()
    * Void set_DeleteUnderlyingObj(Boolean)
    * Boolean get_DeleteUnderlingTiles()
    * Void set_DeleteUnderlingTiles(Boolean)
    * Int32 get_Page()
    * Void set_Page(Int32)
    * Int32 get_XOffset()
    * Void set_XOffset(Int32)
    * Int32 get_YOffset()
    * Void set_YOffset(Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.Xml.XmlNode)
    * Void .ctor(GMAssetCompiler.GMAssets, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Boolean IsSet
    * Int32 Width
    * Int32 Height
    * Boolean ShowGrid
    * Boolean ShowObjects
    * Boolean ShowTiles
    * Boolean ShowBackgrounds
    * Boolean ShowForegrounds
    * Boolean ShowViews
    * Boolean DeleteUnderlyingObj
    * Boolean DeleteUnderlingTiles
    * Int32 Page
    * Int32 XOffset
    * Int32 YOffset
# GMAssetCompiler.GMSpriteInstance
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
# GMAssetCompiler.eGMLayerType
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.eGMLayerType Undefined
    * GMAssetCompiler.eGMLayerType Background
    * GMAssetCompiler.eGMLayerType Instance
    * GMAssetCompiler.eGMLayerType Asset
    * GMAssetCompiler.eGMLayerType Tile
    * GMAssetCompiler.eGMLayerType Particle
# GMAssetCompiler.GMLayerBase
  ## Members
    * System.String get_Name()
    * Void set_Name(System.String)
    * Int32 get_Id()
    * Void set_Id(Int32)
    * GMAssetCompiler.eGMLayerType get_LayerType()
    * Void set_LayerType(GMAssetCompiler.eGMLayerType)
    * Int32 get_Depth()
    * Void set_Depth(Int32)
    * Double get_xoffset()
    * Void set_xoffset(Double)
    * Double get_yoffset()
    * Void set_yoffset(Double)
    * Double get_hspeed()
    * Void set_hspeed(Double)
    * Double get_vspeed()
    * Void set_vspeed(Double)
    * Boolean get_visible()
    * Void set_visible(Boolean)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(System.String, Int32, Int32, Double, Double, Double, Double, Boolean)
    * System.String Name
    * Int32 Id
    * GMAssetCompiler.eGMLayerType LayerType
    * Int32 Depth
    * Double xoffset
    * Double yoffset
    * Double hspeed
    * Double vspeed
    * Boolean visible
# GMAssetCompiler.GMBackgroundLayer
  ## Members
    * System.String get_Name()
    * Void set_Name(System.String)
    * Int32 get_Id()
    * Void set_Id(Int32)
    * GMAssetCompiler.eGMLayerType get_LayerType()
    * Void set_LayerType(GMAssetCompiler.eGMLayerType)
    * Int32 get_Depth()
    * Void set_Depth(Int32)
    * Double get_xoffset()
    * Void set_xoffset(Double)
    * Double get_yoffset()
    * Void set_yoffset(Double)
    * Double get_hspeed()
    * Void set_hspeed(Double)
    * Double get_vspeed()
    * Void set_vspeed(Double)
    * Boolean get_visible()
    * Void set_visible(Boolean)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String, Int32, Int32, GMAssetCompiler.GMBack, Double, Double, Double, Double, Boolean)
    * System.String Name
    * Int32 Id
    * GMAssetCompiler.eGMLayerType LayerType
    * Int32 Depth
    * Double xoffset
    * Double yoffset
    * Double hspeed
    * Double vspeed
    * Boolean visible
    * GMAssetCompiler.GMBack Background
# GMAssetCompiler.GMInstanceLayer
  ## Members
    * System.String get_Name()
    * Void set_Name(System.String)
    * Int32 get_Id()
    * Void set_Id(Int32)
    * GMAssetCompiler.eGMLayerType get_LayerType()
    * Void set_LayerType(GMAssetCompiler.eGMLayerType)
    * Int32 get_Depth()
    * Void set_Depth(Int32)
    * Double get_xoffset()
    * Void set_xoffset(Double)
    * Double get_yoffset()
    * Void set_yoffset(Double)
    * Double get_hspeed()
    * Void set_hspeed(Double)
    * Double get_vspeed()
    * Void set_vspeed(Double)
    * Boolean get_visible()
    * Void set_visible(Boolean)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String, Int32, Int32, System.Collections.Generic.List`1[System.Int32], Double, Double, Double, Double, Boolean)
    * System.String Name
    * Int32 Id
    * GMAssetCompiler.eGMLayerType LayerType
    * Int32 Depth
    * Double xoffset
    * Double yoffset
    * Double hspeed
    * Double vspeed
    * Boolean visible
    * System.Collections.Generic.List`1[System.Int32] InstanceIDs
# GMAssetCompiler.GMAssetLayer
  ## Members
    * System.String get_Name()
    * Void set_Name(System.String)
    * Int32 get_Id()
    * Void set_Id(Int32)
    * GMAssetCompiler.eGMLayerType get_LayerType()
    * Void set_LayerType(GMAssetCompiler.eGMLayerType)
    * Int32 get_Depth()
    * Void set_Depth(Int32)
    * Double get_xoffset()
    * Void set_xoffset(Double)
    * Double get_yoffset()
    * Void set_yoffset(Double)
    * Double get_hspeed()
    * Void set_hspeed(Double)
    * Double get_vspeed()
    * Void set_vspeed(Double)
    * Boolean get_visible()
    * Void set_visible(Boolean)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String, Int32, Int32, System.Collections.Generic.List`1[GMAssetCompiler.GMTile], System.Collections.Generic.List`1[GMAssetCompiler.GMSpriteGraphic], Double, Double, Double, Double, Boolean)
    * System.String Name
    * Int32 Id
    * GMAssetCompiler.eGMLayerType LayerType
    * Int32 Depth
    * Double xoffset
    * Double yoffset
    * Double hspeed
    * Double vspeed
    * Boolean visible
    * System.Collections.Generic.List`1[GMAssetCompiler.GMTile] Tiles
    * System.Collections.Generic.List`1[GMAssetCompiler.GMSpriteGraphic] Sprites
# GMAssetCompiler.GMTileLayer
  ## Members
    * System.String get_Name()
    * Void set_Name(System.String)
    * Int32 get_Id()
    * Void set_Id(Int32)
    * GMAssetCompiler.eGMLayerType get_LayerType()
    * Void set_LayerType(GMAssetCompiler.eGMLayerType)
    * Int32 get_Depth()
    * Void set_Depth(Int32)
    * Double get_xoffset()
    * Void set_xoffset(Double)
    * Double get_yoffset()
    * Void set_yoffset(Double)
    * Double get_hspeed()
    * Void set_hspeed(Double)
    * Double get_vspeed()
    * Void set_vspeed(Double)
    * Boolean get_visible()
    * Void set_visible(Boolean)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String, Int32, Int32, GMAssetCompiler.GMAssets, System.Collections.Generic.Dictionary`2[System.String,System.Object], Double, Double, Double, Double, Boolean)
    * System.String Name
    * Int32 Id
    * GMAssetCompiler.eGMLayerType LayerType
    * Int32 Depth
    * Double xoffset
    * Double yoffset
    * Double hspeed
    * Double vspeed
    * Boolean visible
    * Int32 Index
    * Int32 MapWidth
    * Int32 MapHeight
    * Int32 TileSize
    * Int32 TileHSep
    * Int32 TileVSep
    * Int32 TileColumns
    * System.Collections.Generic.List`1[System.UInt32] Tiles
# GMAssetCompiler.GMRoom
  ## Members
    * Boolean get_InheritCode()
    * Void set_InheritCode(Boolean)
    * System.String get_Caption()
    * Void set_Caption(System.String)
    * Int32 get_Width()
    * Void set_Width(Int32)
    * Int32 get_Height()
    * Void set_Height(Int32)
    * Int32 get_Speed()
    * Void set_Speed(Int32)
    * Boolean get_Persistent()
    * Void set_Persistent(Boolean)
    * Int32 get_Colour()
    * Void set_Colour(Int32)
    * Boolean get_ShowColour()
    * Void set_ShowColour(Boolean)
    * System.String get_Code()
    * Void set_Code(System.String)
    * GMAssetCompiler.eScriptKind get_CodeKind()
    * Void set_CodeKind(GMAssetCompiler.eScriptKind)
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMBack] get_Backgrounds()
    * Void set_Backgrounds(System.Collections.Generic.IList`1[GMAssetCompiler.GMBack])
    * Boolean get_EnableViews()
    * Void set_EnableViews(Boolean)
    * Boolean get_ViewClearScreen()
    * Boolean get_ClearDisplayBuffer()
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMView] get_Views()
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMInstance] get_Instances()
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMTile] get_Tiles()
    * Boolean get_PhysicsWorld()
    * Int32 get_PhysicsWorldTop()
    * Int32 get_PhysicsWorldLeft()
    * Int32 get_PhysicsWorldRight()
    * Int32 get_PhysicsWorldBottom()
    * Single get_PhysicsWorldGravityX()
    * Single get_PhysicsWorldGravityY()
    * Single get_PhysicsWorldPixToMeters()
    * Int32 get_CompiledIndex()
    * Void set_CompiledIndex(Int32)
    * System.String get_SourceFileName()
    * Void set_SourceFileName(System.String)
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMLayerBase] get_Layers()
    * Int32 get_HSnap()
    * Void set_HSnap(Int32)
    * Int32 get_VSnap()
    * Void set_VSnap(Int32)
    * Boolean get_Isometric()
    * Void set_Isometric(Boolean)
    * GMAssetCompiler.GMRoomMakerSettings get_MakerSettings()
    * Void set_MakerSettings(GMAssetCompiler.GMRoomMakerSettings)
    * Void SetFromJson(GMAssetCompiler.GMAssets, System.Collections.Generic.Dictionary`2[System.String,System.Object], Boolean)
    * Void UpdateCreationCode(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.List`1[System.String])
    * Void ProcessFixups(GMAssetCompiler.GMAssets)
    * System.String get_Name()
    * System.Guid get_GUID()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(GMAssetCompiler.GMAssets, System.String)
    * Void .ctor(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void .ctor(GMAssetCompiler.GMAssets, System.IO.Stream)
    * Void .ctor(GMAssetCompiler.GMAssets, System.IO.Stream, Boolean)
    * Boolean InheritCode
    * System.String Caption
    * Int32 Width
    * Int32 Height
    * Int32 Speed
    * Boolean Persistent
    * Int32 Colour
    * Boolean ShowColour
    * System.String Code
    * GMAssetCompiler.eScriptKind CodeKind
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMBack] Backgrounds
    * Boolean EnableViews
    * Boolean ViewClearScreen
    * Boolean ClearDisplayBuffer
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMView] Views
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMInstance] Instances
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMTile] Tiles
    * Boolean PhysicsWorld
    * Int32 PhysicsWorldTop
    * Int32 PhysicsWorldLeft
    * Int32 PhysicsWorldRight
    * Int32 PhysicsWorldBottom
    * Single PhysicsWorldGravityX
    * Single PhysicsWorldGravityY
    * Single PhysicsWorldPixToMeters
    * Int32 CompiledIndex
    * System.String SourceFileName
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMLayerBase] Layers
    * Int32 HSnap
    * Int32 VSnap
    * Boolean Isometric
    * GMAssetCompiler.GMRoomMakerSettings MakerSettings
    * System.String Name
    * System.Guid GUID
    * Int32 CurrentInstanceID
    * Int32 CurrentTileID
    * Int32 CurrentLayerID
# GMAssetCompiler.eScriptKind
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.eScriptKind eGML
    * GMAssetCompiler.eScriptKind eJavaScript
# GMAssetCompiler.GMScript
  ## Members
    * System.String get_Script()
    * Void set_Script(System.String)
    * System.String get_SourceFileName()
    * Void set_SourceFileName(System.String)
    * GMAssetCompiler.eScriptKind get_Kind()
    * Void set_Kind(GMAssetCompiler.eScriptKind)
    * Int32 get_CompiledIndex()
    * Void set_CompiledIndex(Int32)
    * GMAssetCompiler.GMLCode get_Code()
    * Void set_Code(GMAssetCompiler.GMLCode)
    * Void UpdateScript(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.List`1[System.String])
    * System.String get_Name()
    * System.Guid get_GUID()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.String)
    * Void .ctor(GMAssetCompiler.GMAssets, System.String, System.String)
    * Void .ctor(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void .ctor(GMAssetCompiler.GMAssets, System.IO.Stream)
    * Void .ctor(System.String, GMAssetCompiler.eScriptKind)
    * Void .ctor(System.String)
    * System.String Script
    * System.String SourceFileName
    * GMAssetCompiler.eScriptKind Kind
    * Int32 CompiledIndex
    * GMAssetCompiler.GMLCode Code
    * System.String Name
    * System.Guid GUID
    * System.String ResourceTreePath
# GMAssetCompiler.GMSound
  ## Members
    * Int32 get_Kind()
    * Void set_Kind(Int32)
    * System.String get_Extension()
    * System.String get_OrigName()
    * System.String get_WAVCacheName()
    * Void set_WAVCacheName(System.String)
    * System.String get_MP3CacheName()
    * Void set_MP3CacheName(System.String)
    * System.String get_OGGCacheName()
    * Void set_OGGCacheName(System.String)
    * Boolean get_ReadMe()
    * Int32 get_Effects()
    * Double get_Volume()
    * Double get_Pan()
    * Boolean get_Preload()
    * Byte[] get_Data()
    * Boolean get_NewAudio()
    * Boolean get_Compressed()
    * Boolean get_Streamed()
    * Boolean get_UnCompressOnLoad()
    * Int32 get_BitRate()
    * Int32 get_SampleRate()
    * Boolean get_Stereo()
    * System.String get_SourceName()
    * Int32 get_BitDepth()
    * Single get_AudioLength()
    * Int32 get_GroupIndex()
    * Void set_GroupIndex(Int32)
    * Void SetFromJson(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void UpdateSoundFile(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.List`1[System.String])
    * Void CompileToAssetCache()
    * System.String get_Name()
    * System.Guid get_GUID()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.String)
    * Void .ctor(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void .ctor(GMAssetCompiler.GMAssets, System.IO.Stream)
    * Int32 Kind
    * System.String Extension
    * System.String OrigName
    * System.String WAVCacheName
    * System.String MP3CacheName
    * System.String OGGCacheName
    * Boolean ReadMe
    * Int32 Effects
    * Double Volume
    * Double Pan
    * Boolean Preload
    * Byte[] Data
    * Boolean NewAudio
    * Boolean Compressed
    * Boolean Streamed
    * Boolean UnCompressOnLoad
    * Int32 BitRate
    * Int32 SampleRate
    * Boolean Stereo
    * System.String SourceName
    * Int32 BitDepth
    * Single AudioLength
    * Int32 GroupIndex
    * System.String Name
    * System.Guid GUID
    * System.String MissingSoundName
    * System.String DefaultResource
    * Int32 kOgg_Streamed
    * Int32 kWav_Memory
    * Int32 kOgg_Memory
    * Int32 kOgg_Decompress
# GMAssetCompiler.eGMSpriteType
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.eGMSpriteType Bitmap
    * GMAssetCompiler.eGMSpriteType SWF
    * GMAssetCompiler.eGMSpriteType Spine
# GMAssetCompiler.eGMSpriteColKind
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.eGMSpriteColKind Precise
    * GMAssetCompiler.eGMSpriteColKind Rectangle
    * GMAssetCompiler.eGMSpriteColKind Ellipse
    * GMAssetCompiler.eGMSpriteColKind Diamond
# GMAssetCompiler.SpineDataHeader
  ## Members
    * UInt32 get_VersionNumber()
    * UInt32 get_JsonSize()
    * UInt32 get_AtlasSize()
    * UInt32 get_TextureSize()
    * UInt32 get_AtlasTextureWidth()
    * UInt32 get_AtlasTextureHeight()
    * Byte[] ToByteArray()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(UInt32, UInt32, UInt32, UInt32, UInt32)
    * UInt32 VersionNumber
    * UInt32 JsonSize
    * UInt32 AtlasSize
    * UInt32 TextureSize
    * UInt32 AtlasTextureWidth
    * UInt32 AtlasTextureHeight
# GMAssetCompiler.GMSprite
  ## Members
    * GMAssetCompiler.eGMSpriteType get_SpriteType()
    * Int32 get_Width()
    * Int32 get_Height()
    * Int32 get_BBoxLeft()
    * Int32 get_BBoxRight()
    * Int32 get_BBoxBottom()
    * Int32 get_BBoxTop()
    * Boolean get_Transparent()
    * Boolean get_Smooth()
    * Boolean get_Preload()
    * Int32 get_BBoxMode()
    * Boolean get_ColCheck()
    * Int32 get_XOrig()
    * Int32 get_YOrig()
    * Int32 get_FrameCount()
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMBitmap32] get_Images()
    * System.Collections.Generic.IList`1[System.String] get_ImageFileNames()
    * System.String get_SWFfilename()
    * SWFReader.SwfFile get_SWFfile()
    * Single get_SWFprecision()
    * System.String get_SpineFilename()
    * Boolean get_SepMasks()
    * System.Collections.Generic.IList`1[System.Byte[]] get_Masks()
    * Void set_Masks(System.Collections.Generic.IList`1[System.Byte[]])
    * Int32 get_ColKind()
    * Void set_ColKind(Int32)
    * Int32 get_ColTolerance()
    * Void set_ColTolerance(Int32)
    * Boolean get_HTile()
    * Void set_HTile(Boolean)
    * Boolean get_VTile()
    * Void set_VTile(Boolean)
    * System.Collections.Generic.List`1[System.Int32] get_TextureGroups()
    * Void set_TextureGroups(System.Collections.Generic.List`1[System.Int32])
    * Boolean get_For3D()
    * Void set_For3D(Boolean)
    * System.String get_SourceFileName()
    * Void set_SourceFileName(System.String)
    * Void UpdateFileNames(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.List`1[System.String])
    * Void SetFromJson(GMAssetCompiler.GMAssets, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Byte[] GetSWFData()
    * Int32 GenerateSWFFrames(System.String, System.String, Single)
    * Int32 GenerateSpineFrame(System.String, System.String)
    * Int32 GetSpineFrameRootLocation(System.String, Int32[] ByRef)
    * Byte[] GetSpineAtlasTexture(System.String)
    * Byte[] GetSpineData()
    * Void GetAtlasTextureDimensions(System.String, Int32 ByRef, Int32 ByRef)
    * System.String GetSpineEncryptedTextData()
    * System.String GetSpineTextureAtlasName(System.String)
    * System.Collections.Generic.IList`1[System.Byte[]] GetMask()
    * System.Collections.Generic.List`1[System.Byte[]] CreateMask()
    * Byte[] CreateMask(GMAssetCompiler.GMBitmap32, Int32, Int32, Int32)
    * Void MergeMask(Byte[], GMAssetCompiler.GMBitmap32, Int32, Int32, Int32)
    * System.String get_Name()
    * System.Guid get_GUID()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.String)
    * Void .ctor(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void .ctor(GMAssetCompiler.GMAssets, System.IO.Stream)
    * GMAssetCompiler.eGMSpriteType SpriteType
    * Int32 Width
    * Int32 Height
    * Int32 BBoxLeft
    * Int32 BBoxRight
    * Int32 BBoxBottom
    * Int32 BBoxTop
    * Boolean Transparent
    * Boolean Smooth
    * Boolean Preload
    * Int32 BBoxMode
    * Boolean ColCheck
    * Int32 XOrig
    * Int32 YOrig
    * Int32 FrameCount
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMBitmap32] Images
    * System.Collections.Generic.IList`1[System.String] ImageFileNames
    * System.String SWFfilename
    * SWFReader.SwfFile SWFfile
    * Single SWFprecision
    * System.String SpineFilename
    * Boolean SepMasks
    * System.Collections.Generic.IList`1[System.Byte[]] Masks
    * Int32 ColKind
    * Int32 ColTolerance
    * Boolean HTile
    * Boolean VTile
    * System.Collections.Generic.List`1[System.Int32] TextureGroups
    * Boolean For3D
    * System.String SourceFileName
    * System.String Name
    * System.Guid GUID
    * Int32 SpineError_NoError
    * Int32 SpineError_NoAtlas
    * Int32 SpineError_InvalidAtlas
    * Int32 SpineError_InvalidJSON
    * Int32 SpineError_MultipleAtlasPages
# GMAssetCompiler.GMTimeLine
  ## Members
    * System.Collections.Generic.IList`1[GMAssetCompiler.SubTypeAndEvent] get_Entries()
    * System.String get_SourceFileName()
    * Void set_SourceFileName(System.String)
    * Void SetFromJson(GMAssetCompiler.GMAssets, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void UpdateEventCode(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.List`1[System.String])
    * System.String get_Name()
    * System.Guid get_GUID()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.String)
    * Void .ctor(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void .ctor(GMAssetCompiler.GMAssets, System.IO.Stream)
    * System.Collections.Generic.IList`1[GMAssetCompiler.SubTypeAndEvent] Entries
    * System.String SourceFileName
    * System.String Name
    * System.Guid GUID
    * System.String ResourceTreePath
# GMAssetCompiler.GMTrigger
  ## Members
    * System.String get_Name()
    * System.String get_Condition()
    * System.String get_ConstName()
    * Int32 get_Moment()
    * Int32 get_CompiledIndex()
    * Void set_CompiledIndex(Int32)
    * System.String get_SourceFileName()
    * Void set_SourceFileName(System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.Xml.XmlNode)
    * Void .ctor(GMAssetCompiler.GMAssets, System.IO.Stream)
    * System.String Name
    * System.String Condition
    * System.String ConstName
    * Int32 Moment
    * Int32 CompiledIndex
    * System.String SourceFileName
# GMAssetCompiler.IPropertyGrid
  ## Members
    * Flobbster.Windows.Forms.PropertyBag Prepare()
    * System.Drawing.Image PrepareImage()
# GMAssetCompiler.YYStringOffsetAttribute
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Object get_TypeId()
    * Boolean Match(System.Object)
    * Boolean IsDefaultAttribute()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor()
    * System.Object TypeId
# GMAssetCompiler.YYArrayCountAttribute
  ## Members
    * System.Type get_ArrayType()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Object get_TypeId()
    * Boolean Match(System.Object)
    * Boolean IsDefaultAttribute()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor(System.Type)
    * System.Type ArrayType
    * System.Object TypeId
# GMAssetCompiler.YYFixedArrayCountAttribute
  ## Members
    * System.Type get_ArrayType()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Object get_TypeId()
    * Boolean Match(System.Object)
    * Boolean IsDefaultAttribute()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor(System.Type)
    * System.Type ArrayType
    * System.Object TypeId
# GMAssetCompiler.YYOffsetToAttribute
  ## Members
    * System.Type get_ArrayType()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Object get_TypeId()
    * Boolean Match(System.Object)
    * Boolean IsDefaultAttribute()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor(System.Type)
    * System.Type ArrayType
    * System.Object TypeId
# GMAssetCompiler.YYTPageEntry
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 x
    * Int32 y
    * Int32 w
    * Int32 h
    * Int32 tp
# GMAssetCompiler.YYSprite
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 offsName
    * Int32 width
    * Int32 height
    * Int32 bboxLeft
    * Int32 bboxRight
    * Int32 bboxBottom
    * Int32 bboxTop
    * Int32 transparent
    * Int32 smooth
    * Int32 preload
    * Int32 bboxMode
    * Int32 colCheck
    * Int32 xOrigin
    * Int32 yOrigin
    * Int32 count
# GMAssetCompiler.YYBackground
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 offsName
    * Int32 transparent
    * Int32 smooth
    * Int32 preload
    * Int32 texturePageEntry
# GMAssetCompiler.YYPath
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 offsName
    * Int32 kind
    * Int32 closed
    * Int32 precision
    * Int32 count
# GMAssetCompiler.YYPathPoint
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Double x
    * Double y
    * Double speed
# GMAssetCompiler.YYScript
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 name
    * Int32 script
# GMAssetCompiler.YYFont
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 name
    * Int32 fontName
    * Int32 size
    * Int32 bold
    * Int32 italic
    * Int32 first
    * Int32 last
    * Int32 tpe
    * Int32 count
# GMAssetCompiler.YYGlyph
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 x
    * Int32 y
    * Int32 w
    * Int32 h
    * Int32 shift
    * Int32 offset
# GMAssetCompiler.YYEvent
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 libID
    * Int32 id
    * Int32 kind
    * Int32 useRelative
    * Int32 isQuestion
    * Int32 useApplyTo
    * Int32 exeType
    * Int32 name
    * Int32 code
    * Int32 argCount
    * Int32 who
    * Int32 relative
    * Int32 isNot
    * Int32 countArgs
# GMAssetCompiler.YYArgEntry
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 type
    * Int32 arg
# GMAssetCompiler.YYArgType
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 kind
# GMAssetCompiler.YYArgName
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 name
# GMAssetCompiler.YYTimeline
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 name
    * Int32 count
# GMAssetCompiler.YYTimelineEntry
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 key
    * Int32 value
# GMAssetCompiler.YYObject
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 name
    * Int32 spriteIndex
    * Int32 visible
    * Int32 solid
    * Int32 depth
    * Int32 persistent
    * Int32 parent
    * Int32 mask
    * Int32 count
# GMAssetCompiler.YYObjectEntry
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 count
# GMAssetCompiler.YYObjectEntryLevel2
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 key
    * Int32 count
# GMAssetCompiler.YYRoom
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 name
    * Int32 caption
    * Int32 width
    * Int32 height
    * Int32 speed
    * Int32 persistent
    * Int32 colour
    * Int32 showColour
    * Int32 code
    * Int32 enableViews
    * Int32 backgrounds
    * Int32 views
    * Int32 instances
    * Int32 tiles
# GMAssetCompiler.YYRoomBackgrounds
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 count
# GMAssetCompiler.YYRoomViews
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 count
# GMAssetCompiler.YYRoomInstances
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 count
# GMAssetCompiler.YYRoomTiles
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 count
# GMAssetCompiler.YYRoomBackground
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 visible
    * Int32 foreground
    * Int32 index
    * Int32 x
    * Int32 y
    * Int32 hTiled
    * Int32 vTiled
    * Int32 hSpeed
    * Int32 vSpeed
    * Int32 stretch
# GMAssetCompiler.YYRoomView
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 visible
    * Int32 xview
    * Int32 yview
    * Int32 wview
    * Int32 hview
    * Int32 xport
    * Int32 yport
    * Int32 wport
    * Int32 hport
    * Int32 hborder
    * Int32 vborder
    * Int32 hspeed
    * Int32 vspeed
    * Int32 index
# GMAssetCompiler.YYRoomInstance
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 x
    * Int32 y
    * Int32 index
    * Int32 id
    * Int32 code
# GMAssetCompiler.YYRoomTile
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 x
    * Int32 y
    * Int32 index
    * Int32 xo
    * Int32 yo
    * Int32 w
    * Int32 h
    * Int32 depth
    * Int32 id
# GMAssetCompiler.YYHeader
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 debug
    * Int32 name
    * Int32 roomMaxId
    * Int32 roomMaxTileId
    * Int32 id
    * Int32 guid1
    * Int32 guid2
    * Int32 guid3
    * Int32 guid4
    * Int32 count
# GMAssetCompiler.YYRoomOrderEntry
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 order
# GMAssetCompiler.YYOptions
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 fullScreen
    * Int32 interpolatePixels
    * Int32 noBorder
    * Int32 showCursor
    * Int32 scale
    * Int32 sizeable
    * Int32 stayOnTop
    * Int32 windowColour
    * Int32 changeResolution
    * Int32 colorDepth
    * Int32 resolution
    * Int32 frequency
    * Int32 noButtons
    * Int32 sync
    * Int32 screenKey
    * Int32 helpKey
    * Int32 quitKey
    * Int32 saveKey
    * Int32 screenshotKey
    * Int32 closeSec
    * Int32 priority
    * Int32 freeze
    * Int32 showProgress
    * Int32 tpeBackImage
    * Int32 tpeFrontImage
    * Int32 tpeLoadImage
    * Int32 loadTransparent
    * Int32 loadAlpha
    * Int32 scaleProgress
    * Int32 displayErrors
    * Int32 writeErrors
    * Int32 abortErrors
    * Int32 variableErrors
    * Int32 useFrontTouch
    * Int32 useRearTouch
    * Int32 count
# GMAssetCompiler.YYOptionKVP
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 key
    * Int32 value
# GMAssetCompiler.YYSound
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 name
    * Int32 kind
    * Int32 extension
    * Int32 origName
    * Int32 effects
    * Double volume
    * Double pan
    * Int32 preload
# GMAssetCompiler.Loader
  ## Members
    * System.Collections.IEnumerable ParseGMLFile(System.String[])
    * GMAssetCompiler.GMAssets Load(System.String)
    * UInt32 CalcCRC(System.String)
    * Int32 CalcCRC(Byte[])
    * UInt32 CalcCRC(Byte[], Int32)
    * UInt32 HashBitmap(System.Drawing.Bitmap)
    * Boolean Process_Encrypt(Byte[], Int32, System.String, UInt32)
    * Boolean CheckForOldVersions(System.IO.Stream)
    * Boolean CheckFor8_1(System.IO.Stream)
    * Boolean CheckForStudo(System.IO.Stream)
    * Void TagBackgroundTilesets(GMAssetCompiler.GMAssets)
    * GMAssetCompiler.GMAssets LoadGMK(System.IO.Stream, System.String)
    * GMAssetCompiler.GMAssets LoadGMX(System.IO.Stream, System.String)
    * GMAssetCompiler.GMAssets LoadPSP(System.IO.Stream)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Byte[] g_FileBuffer
# GMAssetCompiler.eTexType
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.eTexType eRaw
    * GMAssetCompiler.eTexType eDXT
    * GMAssetCompiler.eTexType ePVR
    * GMAssetCompiler.eTexType e4444
    * GMAssetCompiler.eTexType ePNG
# GMAssetCompiler.eOutputType
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.eOutputType eWAD
    * GMAssetCompiler.eOutputType eHTML5
    * GMAssetCompiler.eOutputType eLLVM
# GMAssetCompiler.IMachineType
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * System.String get_Extension()
    * GMAssetCompiler.eOutputType get_OutputType()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String Name
    * System.String Description
    * System.String Extension
    * GMAssetCompiler.eOutputType OutputType
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.IniSection
  ## Members
    * System.String get_Name()
    * Void set_Name(System.String)
    * System.Collections.Generic.Dictionary`2[System.String,System.String] get_Entries()
    * Void set_Entries(System.Collections.Generic.Dictionary`2[System.String,System.String])
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String)
    * System.String Name
    * System.Collections.Generic.Dictionary`2[System.String,System.String] Entries
# GMAssetCompiler.IniFile
  ## Members
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.IniSection] get_Sections()
    * Void set_Sections(System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.IniSection])
    * Void Save()
    * GMAssetCompiler.IniSection GetSection(System.String)
    * System.String GetEntry(System.String, System.String, System.String)
    * Void AddEntry(System.String, System.String, System.String)
    * System.String GetEntryStripQuotes(System.String, System.String, System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String)
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.IniSection] Sections
# GMAssetCompiler.Machines.Android
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.Windows
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.LLVMWinUAP
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eShaderType ShaderType
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.Linux
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.HTML5
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.IOS
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.LLVMAndroid
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.LLVMiOS
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.LLVMLinux
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.Mac
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.LLVMMac
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.PS3
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.LLVMPS3
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.PS4
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.LLVMPS4
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.PSVita
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.LLVMPSVita
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.LLVMTizen
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.LLVMWin8
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.LLVMWindows
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.LLVMWinPhone
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.XBoxOne
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eShaderType ShaderType
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.LLVMXBoxOne
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eOutputType get_OutputType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eOutputType OutputType
    * GMAssetCompiler.eShaderType ShaderType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.Metro
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.N3DS
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.PSP
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.Symbian
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.Tizen
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.TizenNative
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
# GMAssetCompiler.Machines.WiiU
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.Windows8Native
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eShaderType ShaderType
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.WindowsPhone8
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eShaderType ShaderType
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.WindowsUAP
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eShaderType ShaderType
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Machines.YoYoPlayer
  ## Members
    * System.String get_Name()
    * System.String get_Description()
    * GMAssetCompiler.eOutputType get_OutputType()
    * System.String get_Extension()
    * Int32 get_TPageWidth()
    * Int32 get_TPageHeight()
    * Int32 get_TPageBorderTop()
    * Int32 get_TPageBorderBottom()
    * Int32 get_TPageBorderLeft()
    * Int32 get_TPageBorderRight()
    * GMAssetCompiler.eTexType get_OpaqueTextureType()
    * GMAssetCompiler.eTexType get_AlphaTextureType()
    * GMAssetCompiler.eShaderType get_ShaderType()
    * Boolean get_LowerCaseFileNames()
    * UInt16 Convert4444(Int32, Int32, Int32, Int32)
    * UInt32 Convert8888(Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eOutputType OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * GMAssetCompiler.eTexType OpaqueTextureType
    * GMAssetCompiler.eTexType AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# GMAssetCompiler.eLex
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.eLex None
    * GMAssetCompiler.eLex WhiteSpace
    * GMAssetCompiler.eLex Decimal
    * GMAssetCompiler.eLex ID
    * GMAssetCompiler.eLex reserved
    * GMAssetCompiler.eLex reserved2
    * GMAssetCompiler.eLex reserved3
    * GMAssetCompiler.eLex String
    * GMAssetCompiler.eLex StringNoEncode
    * GMAssetCompiler.eLex LeftBracket
    * GMAssetCompiler.eLex RightBracket
    * GMAssetCompiler.eLex Plus
    * GMAssetCompiler.eLex PlusPlus
    * GMAssetCompiler.eLex Minus
    * GMAssetCompiler.eLex Carrot
    * GMAssetCompiler.eLex Ampersand
    * GMAssetCompiler.eLex And
    * GMAssetCompiler.eLex Bar
    * GMAssetCompiler.eLex Or
    * GMAssetCompiler.eLex QuestionMark
    * GMAssetCompiler.eLex ShiftLeft
    * GMAssetCompiler.eLex ShiftRight
    * GMAssetCompiler.eLex Squiggle
    * GMAssetCompiler.eLex Divide
    * GMAssetCompiler.eLex Exclamation
    * GMAssetCompiler.eLex Quotes
    * GMAssetCompiler.eLex SingleQuotes
    * GMAssetCompiler.eLex Dollar
    * GMAssetCompiler.eLex Percent
    * GMAssetCompiler.eLex Star
    * GMAssetCompiler.eLex Equals
    * GMAssetCompiler.eLex NotEqualTo
    * GMAssetCompiler.eLex LeftSquareBracket
    * GMAssetCompiler.eLex RightSquareBracket
    * GMAssetCompiler.eLex Comma
    * GMAssetCompiler.eLex Colon
    * GMAssetCompiler.eLex SemiColon
    * GMAssetCompiler.eLex LCB
    * GMAssetCompiler.eLex RCB
    * GMAssetCompiler.eLex LessThan
    * GMAssetCompiler.eLex GreaterThan
    * GMAssetCompiler.eLex Dot
    * GMAssetCompiler.eLex Not
    * GMAssetCompiler.eLex EqualEqualEqual
    * GMAssetCompiler.eLex NotEqual
    * GMAssetCompiler.eLex AndEqual
    * GMAssetCompiler.eLex EorEqual
    * GMAssetCompiler.eLex MinusEqual
    * GMAssetCompiler.eLex PlusEqual
    * GMAssetCompiler.eLex XorEqual
    * GMAssetCompiler.eLex EqualEqual
    * GMAssetCompiler.eLex AndAnd
    * GMAssetCompiler.eLex OrOr
    * GMAssetCompiler.eLex NewLine
    * GMAssetCompiler.eLex Comment
    * GMAssetCompiler.eLex EOF
# GMAssetCompiler.Lex
  ## Members
    * System.String get_yyText()
    * Double get_yyValue()
    * GMAssetCompiler.eLex get_yyToken()
    * System.String get_Text()
    * Void set_Text(System.String)
    * Boolean get_CaseSensitive()
    * Void set_CaseSensitive(Boolean)
    * Void AddSymbol(System.String, GMAssetCompiler.eLex)
    * Void AddCommand(System.String, GMAssetCompiler.eLex)
    * GMAssetCompiler.eLex CheckToken(System.String)
    * Void Push()
    * Void EnqueueLex(GMAssetCompiler.eLex, System.String, Double)
    * Char NextChar()
    * GMAssetCompiler.eLex MultiReadToken(Char, GMAssetCompiler.eLex)
    * GMAssetCompiler.eLex yylex()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.YYObfuscate)
    * System.String yyText
    * Double yyValue
    * GMAssetCompiler.eLex yyToken
    * System.String Text
    * Boolean CaseSensitive
# GMAssetCompiler.LexTree
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.eLex, System.String)
    * System.Collections.Generic.List`1[GMAssetCompiler.LexTree] Children
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.VFNode] Used
    * System.String Name
    * GMAssetCompiler.VFNode Node
    * GMAssetCompiler.eLex Token
    * System.String Text
    * Double _value
    * Boolean anon
# GMAssetCompiler.VFNode
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String)
    * Int32 Count
    * System.String Name
    * System.Collections.Generic.List`1[GMAssetCompiler.LexTree] pFunction
    * Boolean AlreadyRemoved
# GMAssetCompiler.YYObfuscate
  ## Members
    * Boolean get_PrettyPrint()
    * Void set_PrettyPrint(Boolean)
    * Boolean get_Obfuscate()
    * Void set_Obfuscate(Boolean)
    * Boolean get_EncodeStrings()
    * Void set_EncodeStrings(Boolean)
    * Boolean get_RemovedUnused()
    * Void set_RemovedUnused(Boolean)
    * Int32 get_UglyWidth()
    * Void set_UglyWidth(Int32)
    * Boolean get_Verbose()
    * Void set_Verbose(Boolean)
    * Int32 RemoveFunctionReferences(System.Collections.Generic.List`1[GMAssetCompiler.LexTree], Int32)
    * Int32 RemoveFunctions(System.Collections.Generic.List`1[GMAssetCompiler.LexTree], Int32, Int32)
    * Void AddCount(System.Collections.Generic.List`1[GMAssetCompiler.LexTree], Int32)
    * Int32 CheckHex(System.Collections.Generic.List`1[GMAssetCompiler.LexTree], Int32)
    * Void WriteNodeList(System.Collections.Generic.List`1[GMAssetCompiler.LexTree], System.IO.StreamWriter)
    * Void WriteOut_MaskLookup(System.IO.StreamWriter)
    * Void DoObfuscate(System.Collections.Generic.IEnumerable`1[System.String], System.String, System.Collections.Generic.IEnumerable`1[System.String], GMAssetCompiler.GMAssets)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Boolean PrettyPrint
    * Boolean Obfuscate
    * Boolean EncodeStrings
    * Boolean RemovedUnused
    * Int32 UglyWidth
    * Boolean Verbose
    * System.Collections.Generic.List`1[GMAssetCompiler.LexTree] m_TokenTree
    * System.Collections.Generic.Dictionary`2[System.String,System.String] m_Encoder
    * System.Collections.Generic.Dictionary`2[System.String,System.Int32] m_StringTable
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.VFNode] m_FunctionList
    * System.Collections.Generic.Dictionary`2[System.String,System.String] m_MaskConvert
# NDesk.Options.OptionValueCollection
  ## Members
    * Void Add(System.String)
    * Void Clear()
    * Boolean Contains(System.String)
    * Void CopyTo(System.String[], Int32)
    * Boolean Remove(System.String)
    * Int32 get_Count()
    * Boolean get_IsReadOnly()
    * System.Collections.Generic.IEnumerator`1[System.String] GetEnumerator()
    * Int32 IndexOf(System.String)
    * Void Insert(Int32, System.String)
    * Void RemoveAt(Int32)
    * System.String get_Item(Int32)
    * Void set_Item(Int32, System.String)
    * System.Collections.Generic.List`1[System.String] ToList()
    * System.String[] ToArray()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Int32 Count
    * Boolean IsReadOnly
    * System.String Item [Int32]
# NDesk.Options.OptionContext
  ## Members
    * NDesk.Options.Option get_Option()
    * Void set_Option(NDesk.Options.Option)
    * System.String get_OptionName()
    * Void set_OptionName(System.String)
    * Int32 get_OptionIndex()
    * Void set_OptionIndex(Int32)
    * NDesk.Options.OptionSet get_OptionSet()
    * NDesk.Options.OptionValueCollection get_OptionValues()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(NDesk.Options.OptionSet)
    * NDesk.Options.Option Option
    * System.String OptionName
    * Int32 OptionIndex
    * NDesk.Options.OptionSet OptionSet
    * NDesk.Options.OptionValueCollection OptionValues
# NDesk.Options.OptionValueType
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * NDesk.Options.OptionValueType None
    * NDesk.Options.OptionValueType Optional
    * NDesk.Options.OptionValueType Required
# NDesk.Options.Option
  ## Members
    * System.String get_Prototype()
    * System.String get_Description()
    * NDesk.Options.OptionValueType get_OptionValueType()
    * Int32 get_MaxValueCount()
    * System.String[] GetNames()
    * System.String[] GetValueSeparators()
    * Void Invoke(NDesk.Options.OptionContext)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * System.String Prototype
    * System.String Description
    * NDesk.Options.OptionValueType OptionValueType
    * Int32 MaxValueCount
# NDesk.Options.OptionException
  ## Members
    * System.String get_OptionName()
    * Void GetObjectData(System.Runtime.Serialization.SerializationInfo, System.Runtime.Serialization.StreamingContext)
    * System.String get_Message()
    * System.Collections.IDictionary get_Data()
    * System.Exception GetBaseException()
    * System.Exception get_InnerException()
    * System.Reflection.MethodBase get_TargetSite()
    * System.String get_StackTrace()
    * System.String get_HelpLink()
    * Void set_HelpLink(System.String)
    * System.String get_Source()
    * Void set_Source(System.String)
    * System.String ToString()
    * Int32 get_HResult()
    * System.Type GetType()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(System.String, System.String)
    * Void .ctor(System.String, System.String, System.Exception)
    * System.String OptionName
    * System.String Message
    * System.Collections.IDictionary Data
    * System.Exception InnerException
    * System.Reflection.MethodBase TargetSite
    * System.String StackTrace
    * System.String HelpLink
    * System.String Source
    * Int32 HResult
# NDesk.Options.OptionAction`2[TKey,TValue]
  ## Members
    * Void Invoke(TKey, TValue)
    * System.IAsyncResult BeginInvoke(TKey, TValue, System.AsyncCallback, System.Object)
    * Void EndInvoke(System.IAsyncResult)
    * Void GetObjectData(System.Runtime.Serialization.SerializationInfo, System.Runtime.Serialization.StreamingContext)
    * Boolean Equals(System.Object)
    * System.Delegate[] GetInvocationList()
    * Int32 GetHashCode()
    * System.Object DynamicInvoke(System.Object[])
    * System.Reflection.MethodInfo get_Method()
    * System.Object get_Target()
    * System.Object Clone()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor(System.Object, IntPtr)
    * System.Reflection.MethodInfo Method
    * System.Object Target
# NDesk.Options.OptionSet
  ## Members
    * System.Converter`2[System.String,System.String] get_MessageLocalizer()
    * NDesk.Options.OptionSet Add(NDesk.Options.Option)
    * NDesk.Options.OptionSet Add(System.String, System.Action`1[System.String])
    * NDesk.Options.OptionSet Add(System.String, System.String, System.Action`1[System.String])
    * NDesk.Options.OptionSet Add(System.String, NDesk.Options.OptionAction`2[System.String,System.String])
    * NDesk.Options.OptionSet Add(System.String, System.String, NDesk.Options.OptionAction`2[System.String,System.String])
    * NDesk.Options.OptionSet Add[T](System.String, System.Action`1[T])
    * NDesk.Options.OptionSet Add[T](System.String, System.String, System.Action`1[T])
    * NDesk.Options.OptionSet Add[TKey,TValue](System.String, NDesk.Options.OptionAction`2[TKey,TValue])
    * NDesk.Options.OptionSet Add[TKey,TValue](System.String, System.String, NDesk.Options.OptionAction`2[TKey,TValue])
    * System.Collections.Generic.List`1[System.String] Parse(System.Collections.Generic.IEnumerable`1[System.String])
    * Void WriteOptionDescriptions(System.IO.TextWriter)
    * System.Collections.Generic.IEqualityComparer`1[System.String] get_Comparer()
    * NDesk.Options.Option get_Item(System.String)
    * Boolean Contains(System.String)
    * Boolean Remove(System.String)
    * Int32 get_Count()
    * NDesk.Options.Option get_Item(Int32)
    * Void set_Item(Int32, NDesk.Options.Option)
    * Void Add(NDesk.Options.Option)
    * Void Clear()
    * Void CopyTo(NDesk.Options.Option[], Int32)
    * Boolean Contains(NDesk.Options.Option)
    * System.Collections.Generic.IEnumerator`1[NDesk.Options.Option] GetEnumerator()
    * Int32 IndexOf(NDesk.Options.Option)
    * Void Insert(Int32, NDesk.Options.Option)
    * Boolean Remove(NDesk.Options.Option)
    * Void RemoveAt(Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(System.Converter`2[System.String,System.String])
    * System.Converter`2[System.String,System.String] MessageLocalizer
    * System.Collections.Generic.IEqualityComparer`1[System.String] Comparer
    * NDesk.Options.Option Item [System.String]
    * Int32 Count
    * NDesk.Options.Option Item [Int32]
# NDesk.Options.OptionSet+ActionOption
  ## Members
    * System.String get_Prototype()
    * System.String get_Description()
    * NDesk.Options.OptionValueType get_OptionValueType()
    * Int32 get_MaxValueCount()
    * System.String[] GetNames()
    * System.String[] GetValueSeparators()
    * Void Invoke(NDesk.Options.OptionContext)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String, System.String, Int32, System.Action`1[NDesk.Options.OptionValueCollection])
    * System.String Prototype
    * System.String Description
    * NDesk.Options.OptionValueType OptionValueType
    * Int32 MaxValueCount
# NDesk.Options.OptionSet+ActionOption`1[T]
  ## Members
    * System.String get_Prototype()
    * System.String get_Description()
    * NDesk.Options.OptionValueType get_OptionValueType()
    * Int32 get_MaxValueCount()
    * System.String[] GetNames()
    * System.String[] GetValueSeparators()
    * Void Invoke(NDesk.Options.OptionContext)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String, System.String, System.Action`1[T])
    * System.String Prototype
    * System.String Description
    * NDesk.Options.OptionValueType OptionValueType
    * Int32 MaxValueCount
# NDesk.Options.OptionSet+ActionOption`2[TKey,TValue]
  ## Members
    * System.String get_Prototype()
    * System.String get_Description()
    * NDesk.Options.OptionValueType get_OptionValueType()
    * Int32 get_MaxValueCount()
    * System.String[] GetNames()
    * System.String[] GetValueSeparators()
    * Void Invoke(NDesk.Options.OptionContext)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String, System.String, NDesk.Options.OptionAction`2[TKey,TValue])
    * System.String Prototype
    * System.String Description
    * NDesk.Options.OptionValueType OptionValueType
    * Int32 MaxValueCount
# GMAssetCompiler.Output.ILLVM
  ## Members
    * System.String get_Name()
    * System.String get_Extension()
    * System.Collections.Generic.List`1[System.String] get_Archs()
    * Boolean ClangCompile(System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean ClangLink(System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * Boolean CreateWADObj(System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * System.String CreateExeName(System.String, System.String)
    * System.String GetWADExtension()
    * System.String GetArchDir(System.String)
    * Boolean HasSeparateWAD()
    * Boolean HasWriteProject()
    * Boolean HasCompileAndLink()
    * Boolean WriteProject(System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[GMAssetCompiler.ExtraFile], GMAssetCompiler.GMAssets)
    * System.String Name
    * System.String Extension
    * System.Collections.Generic.List`1[System.String] Archs
# GMAssetCompiler.Output.LLVM_WindowsUAP
  ## Members
    * System.String get_SDKDir()
    * Void set_SDKDir(System.String)
    * System.String get_Name()
    * System.String get_Extension()
    * System.Collections.Generic.List`1[System.String] get_Archs()
    * Void Error(System.String, System.Object[])
    * Boolean ClangCompile(System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean CreateWADObj(System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * Boolean ClangLink(System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * System.String CreateExeName(System.String, System.String)
    * Boolean HasSeparateWAD()
    * Boolean HasWriteProject()
    * Boolean HasCompileAndLink()
    * Boolean WriteProject(System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[GMAssetCompiler.ExtraFile], GMAssetCompiler.GMAssets)
    * System.String GetWADExtension()
    * System.String GetArchDir(System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String SDKDir
    * System.String Name
    * System.String Extension
    * System.Collections.Generic.List`1[System.String] Archs
# GMAssetCompiler.Output.FunctionClassification
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * UInt64 value__
    * GMAssetCompiler.Output.FunctionClassification None
    * GMAssetCompiler.Output.FunctionClassification Internet
    * GMAssetCompiler.Output.FunctionClassification Joystick
    * GMAssetCompiler.Output.FunctionClassification Gamepad
    * GMAssetCompiler.Output.FunctionClassification Immersion
    * GMAssetCompiler.Output.FunctionClassification ReadScreenPixels
    * GMAssetCompiler.Output.FunctionClassification Math
    * GMAssetCompiler.Output.FunctionClassification Action
    * GMAssetCompiler.Output.FunctionClassification D3D_State
    * GMAssetCompiler.Output.FunctionClassification D3D_Primitive
    * GMAssetCompiler.Output.FunctionClassification DataStructure
    * GMAssetCompiler.Output.FunctionClassification File_Legacy
    * GMAssetCompiler.Output.FunctionClassification Ini
    * GMAssetCompiler.Output.FunctionClassification Filename
    * GMAssetCompiler.Output.FunctionClassification Directory
    * GMAssetCompiler.Output.FunctionClassification Shell
    * GMAssetCompiler.Output.FunctionClassification Obsolete
    * GMAssetCompiler.Output.FunctionClassification Http
    * GMAssetCompiler.Output.FunctionClassification JsonZip
    * GMAssetCompiler.Output.FunctionClassification Debug
    * GMAssetCompiler.Output.FunctionClassification Motion
    * GMAssetCompiler.Output.FunctionClassification Collision
    * GMAssetCompiler.Output.FunctionClassification Instance
    * GMAssetCompiler.Output.FunctionClassification Room
    * GMAssetCompiler.Output.FunctionClassification Game
    * GMAssetCompiler.Output.FunctionClassification Display
    * GMAssetCompiler.Output.FunctionClassification Device
    * GMAssetCompiler.Output.FunctionClassification Window
    * GMAssetCompiler.Output.FunctionClassification Draw
    * GMAssetCompiler.Output.FunctionClassification Texture
    * GMAssetCompiler.Output.FunctionClassification Graphics
    * GMAssetCompiler.Output.FunctionClassification String
    * GMAssetCompiler.Output.FunctionClassification Tile
    * GMAssetCompiler.Output.FunctionClassification Surface
    * GMAssetCompiler.Output.FunctionClassification Skeleton
    * GMAssetCompiler.Output.FunctionClassification IO
    * GMAssetCompiler.Output.FunctionClassification GMSystem
    * GMAssetCompiler.Output.FunctionClassification Array
    * GMAssetCompiler.Output.FunctionClassification External
    * GMAssetCompiler.Output.FunctionClassification Push
    * GMAssetCompiler.Output.FunctionClassification Date
    * GMAssetCompiler.Output.FunctionClassification Particle
    * GMAssetCompiler.Output.FunctionClassification Resource
    * GMAssetCompiler.Output.FunctionClassification Html5
    * GMAssetCompiler.Output.FunctionClassification Sound
    * GMAssetCompiler.Output.FunctionClassification Audio
    * GMAssetCompiler.Output.FunctionClassification Event
    * GMAssetCompiler.Output.FunctionClassification Script
    * GMAssetCompiler.Output.FunctionClassification Text
    * GMAssetCompiler.Output.FunctionClassification Analytics
    * GMAssetCompiler.Output.FunctionClassification Object
    * GMAssetCompiler.Output.FunctionClassification Asset
    * GMAssetCompiler.Output.FunctionClassification Achievement
    * GMAssetCompiler.Output.FunctionClassification Cloud
    * GMAssetCompiler.Output.FunctionClassification Ads
    * GMAssetCompiler.Output.FunctionClassification Os
    * GMAssetCompiler.Output.FunctionClassification iap
    * GMAssetCompiler.Output.FunctionClassification Facebook
    * GMAssetCompiler.Output.FunctionClassification Physics
    * GMAssetCompiler.Output.FunctionClassification SWF
    * GMAssetCompiler.Output.FunctionClassification PlatformSpecific
    * GMAssetCompiler.Output.FunctionClassification Buffer
    * GMAssetCompiler.Output.FunctionClassification Steam
    * GMAssetCompiler.Output.FunctionClassification Steam_UGC
    * GMAssetCompiler.Output.FunctionClassification Shader
    * GMAssetCompiler.Output.FunctionClassification Vertex
# GMAssetCompiler.CPPExpr
  ## Members
    * GMAssetCompiler.eVM_Type get_Type()
    * Void set_Type(GMAssetCompiler.eVM_Type)
    * GMAssetCompiler.CPPVarTracking get_VarTracking()
    * Void set_VarTracking(GMAssetCompiler.CPPVarTracking)
    * System.Text.StringBuilder get_Expr()
    * Void set_Expr(System.Text.StringBuilder)
    * System.Text.StringBuilder get_Array1()
    * Void set_Array1(System.Text.StringBuilder)
    * System.Text.StringBuilder get_Array2()
    * Void set_Array2(System.Text.StringBuilder)
    * System.String get_Name()
    * Void set_Name(System.String)
    * UInt32 get_Crc()
    * Void set_Crc(UInt32)
    * Int32 get_StoreCount()
    * Void set_StoreCount(Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * GMAssetCompiler.eVM_Type Type
    * GMAssetCompiler.CPPVarTracking VarTracking
    * System.Text.StringBuilder Expr
    * System.Text.StringBuilder Array1
    * System.Text.StringBuilder Array2
    * System.String Name
    * UInt32 Crc
    * Int32 StoreCount
    * System.Text.StringBuilder ms_Expr
    * System.Text.StringBuilder ms_Array1
    * System.Text.StringBuilder ms_Array2
# GMAssetCompiler.CPPVarRef
  ## Members
    * Int32 get_ObjInd()
    * Void set_ObjInd(Int32)
    * Int32 get_ContextID()
    * Void set_ContextID(Int32)
    * GMAssetCompiler.CPPExpr get_ObjRefExpr()
    * Void set_ObjRefExpr(GMAssetCompiler.CPPExpr)
    * System.String get_VarInd()
    * Void set_VarInd(System.String)
    * System.String get_ArrInd()
    * Void set_ArrInd(System.String)
    * System.String get_Name()
    * Void set_Name(System.String)
    * System.String get_IndexName()
    * Void set_IndexName(System.String)
    * Boolean get_Volatile()
    * Void set_Volatile(Boolean)
    * Boolean get_Local()
    * Void set_Local(Boolean)
    * GMAssetCompiler.eKind get_Kind()
    * Void set_Kind(GMAssetCompiler.eKind)
    * GMAssetCompiler.eKind get_PrevKind()
    * Void set_PrevKind(GMAssetCompiler.eKind)
    * GMAssetCompiler.GMLVariable get_Var()
    * Void set_Var(GMAssetCompiler.GMLVariable)
    * Boolean get_SelfOrOther()
    * Void set_SelfOrOther(Boolean)
    * Boolean get_BuiltIn()
    * Void set_BuiltIn(Boolean)
    * System.String get_BuiltInName()
    * Void set_BuiltInName(System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 ObjInd
    * Int32 ContextID
    * GMAssetCompiler.CPPExpr ObjRefExpr
    * System.String VarInd
    * System.String ArrInd
    * System.String Name
    * System.String IndexName
    * Boolean Volatile
    * Boolean Local
    * GMAssetCompiler.eKind Kind
    * GMAssetCompiler.eKind PrevKind
    * GMAssetCompiler.GMLVariable Var
    * Boolean SelfOrOther
    * Boolean BuiltIn
    * System.String BuiltInName
# GMAssetCompiler.CPPAssignmentRef
  ## Members
    * System.String get_Name()
    * Void set_Name(System.String)
    * System.String get_Expression()
    * Void set_Expression(System.String)
    * Boolean get_VarArgsRef()
    * Void set_VarArgsRef(Boolean)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Expression
    * Boolean VarArgsRef
# GMAssetCompiler.eLoadRefKind
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.eLoadRefKind eAssignment
    * GMAssetCompiler.eLoadRefKind eLoad
    * GMAssetCompiler.eLoadRefKind eString
# GMAssetCompiler.CPPLoadRef
  ## Members
    * GMAssetCompiler.eLoadRefKind get_Kind()
    * Void set_Kind(GMAssetCompiler.eLoadRefKind)
    * GMAssetCompiler.CPPAssignmentRef get_Assignment()
    * Void set_Assignment(GMAssetCompiler.CPPAssignmentRef)
    * GMAssetCompiler.CPPVarRef get_Load()
    * Void set_Load(GMAssetCompiler.CPPVarRef)
    * System.String get_String()
    * Void set_String(System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.eLoadRefKind, GMAssetCompiler.CPPAssignmentRef, GMAssetCompiler.CPPVarRef)
    * Void .ctor(System.String)
    * GMAssetCompiler.eLoadRefKind Kind
    * GMAssetCompiler.CPPAssignmentRef Assignment
    * GMAssetCompiler.CPPVarRef Load
    * System.String String
# GMAssetCompiler.CPPLocalVar
  ## Members
    * System.String get_Name()
    * Void set_Name(System.String)
    * GMAssetCompiler.eVM_Type get_Type()
    * Void set_Type(GMAssetCompiler.eVM_Type)
    * GMAssetCompiler.CPPVarRef get_VarRef()
    * Void set_VarRef(GMAssetCompiler.CPPVarRef)
    * Boolean get_Loaded()
    * Void set_Loaded(Boolean)
    * Int32 get_StoreCount()
    * Void set_StoreCount(Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String)
    * System.String Name
    * GMAssetCompiler.eVM_Type Type
    * GMAssetCompiler.CPPVarRef VarRef
    * Boolean Loaded
    * Int32 StoreCount
# GMAssetCompiler.CPPVarTracking
  ## Members
    * System.Collections.Generic.List`1[GMAssetCompiler.CPPVarRef] get_StoreRefs()
    * Void set_StoreRefs(System.Collections.Generic.List`1[GMAssetCompiler.CPPVarRef])
    * System.Collections.Generic.List`1[GMAssetCompiler.CPPLoadRef] get_LoadRefs()
    * Void set_LoadRefs(System.Collections.Generic.List`1[GMAssetCompiler.CPPLoadRef])
    * Int32 get_ID()
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.CPPLocalVar] get_DeclaredVars()
    * Void set_DeclaredVars(System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.CPPLocalVar])
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.CPPLocalVar] get_UnDeclaredVars()
    * Void set_UnDeclaredVars(System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.CPPLocalVar])
    * Void AddRange(GMAssetCompiler.CPPVarTracking)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(GMAssetCompiler.CPPVarTracking)
    * System.Collections.Generic.List`1[GMAssetCompiler.CPPVarRef] StoreRefs
    * System.Collections.Generic.List`1[GMAssetCompiler.CPPLoadRef] LoadRefs
    * Int32 ID
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.CPPLocalVar] DeclaredVars
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.CPPLocalVar] UnDeclaredVars
    * Int32 ms_CurrentID
# GMAssetCompiler.IGML2Base
  ## Members
    * GMAssetCompiler.GMLCode get_Code()
    * Void set_Code(GMAssetCompiler.GMLCode)
    * Void Compile(GMAssetCompiler.GMAssets, GMAssetCompiler.GMLCode)
    * Void CompileJS(GMAssetCompiler.GMAssets, GMAssetCompiler.GMLCode)
    * GMAssetCompiler.GMLCode Code
# GMAssetCompiler.GML2Base
  ## Members
    * GMAssetCompiler.GMLCode get_Code()
    * Void set_Code(GMAssetCompiler.GMLCode)
    * GMAssetCompiler.VMBuffer get_VMB()
    * Void set_VMB(GMAssetCompiler.VMBuffer)
    * Boolean get_ErrorFlag()
    * Void set_ErrorFlag(Boolean)
    * Boolean get_ContinueIllegal()
    * Void set_ContinueIllegal(Boolean)
    * Void Compile(GMAssetCompiler.GMAssets, GMAssetCompiler.GMLCode)
    * Void CompileJS(GMAssetCompiler.GMAssets, GMAssetCompiler.GMLCode)
    * Void Error(System.String, GMAssetCompiler.GMLToken)
    * Void Warning(System.String, GMAssetCompiler.GMLToken)
    * GMAssetCompiler.GMLToken RewriteTree(GMAssetCompiler.GMLToken)
    * GMAssetCompiler.GMLToken OptimizeTree(GMAssetCompiler.GMLToken)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * GMAssetCompiler.GMLCode Code
    * GMAssetCompiler.VMBuffer VMB
    * Boolean ErrorFlag
    * Boolean ContinueIllegal
    * Int32 ms_numErrors
    * Int32 ms_continueCount
    * System.Collections.Generic.Stack`1[GMAssetCompiler.eVM_Type] ms_switchCount
    * Int32 ms_withCount
    * System.Collections.Generic.Stack`1[System.Char] ms_switchWithOrder
# GMAssetCompiler.GML2CPP
  ## Members
    * System.String GMLTypeToCPPType(GMAssetCompiler.eVM_Type)
    * System.String GMLTypeToCPPTypeRef(GMAssetCompiler.eVM_Type)
    * System.String GMLDeclFromVar(GMAssetCompiler.CPPLocalVar)
    * Void WriteGMLIDHeaderFile(System.String, System.Collections.Generic.List`1[System.String])
    * Void Compile(GMAssetCompiler.GMAssets, GMAssetCompiler.GMLCode)
    * Int64 get_OutputBase()
    * Void set_OutputBase(Int64)
    * System.Collections.Generic.Stack`1[System.Boolean] get_VariableExpressionStack()
    * Void set_VariableExpressionStack(System.Collections.Generic.Stack`1[System.Boolean])
    * System.Collections.Generic.Stack`1[GMAssetCompiler.eVM_Type] get_TypeStack()
    * Void set_TypeStack(System.Collections.Generic.Stack`1[GMAssetCompiler.eVM_Type])
    * System.Collections.Generic.Stack`1[GMAssetCompiler.VMLabel] get_LoopEnv()
    * Void set_LoopEnv(System.Collections.Generic.Stack`1[GMAssetCompiler.VMLabel])
    * System.Collections.Generic.Stack`1[GMAssetCompiler.VMLabel] get_LoopEndEnv()
    * Void set_LoopEndEnv(System.Collections.Generic.Stack`1[GMAssetCompiler.VMLabel])
    * System.Collections.Generic.Dictionary`2[System.Int32,System.Collections.Generic.List`1[System.Int64]] get_VarPatches()
    * Void set_VarPatches(System.Collections.Generic.Dictionary`2[System.Int32,System.Collections.Generic.List`1[System.Int64]])
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.CPPLocalVar] get_CPPVars()
    * Void set_CPPVars(System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.CPPLocalVar])
    * System.Collections.Generic.Dictionary`2[System.String,System.Byte[]] get_CPPStrings()
    * Void set_CPPStrings(System.Collections.Generic.Dictionary`2[System.String,System.Byte[]])
    * System.String get_FileName()
    * Void set_FileName(System.String)
    * System.Collections.Generic.List`1[System.String] get_UsedStrings()
    * Void set_UsedStrings(System.Collections.Generic.List`1[System.String])
    * System.Collections.Generic.List`1[GMAssetCompiler.GMLCPPFunction] get_ScriptsUsed()
    * Void set_ScriptsUsed(System.Collections.Generic.List`1[GMAssetCompiler.GMLCPPFunction])
    * Boolean get_IsScript()
    * Void set_IsScript(Boolean)
    * Boolean get_UsesArgs()
    * Void set_UsesArgs(Boolean)
    * Boolean get_UsesConcat()
    * Void set_UsesConcat(Boolean)
    * Boolean get_ForceInline()
    * Void set_ForceInline(Boolean)
    * Boolean get_UsesConcatThisExpression()
    * Void set_UsesConcatThisExpression(Boolean)
    * Int32 get_NumConcats()
    * Void set_NumConcats(Int32)
    * Int32 get_MaxNumConcats()
    * Void set_MaxNumConcats(Int32)
    * System.String get_ReturnLabel()
    * Void set_ReturnLabel(System.String)
    * Boolean get_ReturnLabelUsed()
    * Void set_ReturnLabelUsed(Boolean)
    * GMAssetCompiler.GMLCPPFunction get_FuncSignature()
    * Void set_FuncSignature(GMAssetCompiler.GMLCPPFunction)
    * System.Collections.Generic.Stack`1[GMAssetCompiler.CPPVarTracking] get_VarTracking()
    * Void set_VarTracking(System.Collections.Generic.Stack`1[GMAssetCompiler.CPPVarTracking])
    * System.Collections.Generic.Stack`1[System.Int32] get_ReturnStack()
    * Void set_ReturnStack(System.Collections.Generic.Stack`1[System.Int32])
    * System.Collections.Generic.List`1[System.Int32] get_ReturnValueUsed()
    * Void set_ReturnValueUsed(System.Collections.Generic.List`1[System.Int32])
    * Int32 get_NumberReturnValues()
    * Void set_NumberReturnValues(Int32)
    * Boolean get_GenerateArgumentCount()
    * Void set_GenerateArgumentCount(Boolean)
    * System.Collections.Generic.Dictionary`2[System.String,System.Double] get_ConstantDefs()
    * Void set_ConstantDefs(System.Collections.Generic.Dictionary`2[System.String,System.Double])
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.GMLCPPFunction] get_LocalLegacyUsed()
    * Void set_LocalLegacyUsed(System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.GMLCPPFunction])
    * System.Collections.Generic.List`1[System.Int32] get_ArgumentStoredTo()
    * Void set_ArgumentStoredTo(System.Collections.Generic.List`1[System.Int32])
    * System.Collections.Generic.List`1[System.String] get_Strings()
    * Void set_Strings(System.Collections.Generic.List`1[System.String])
    * Int32 get_LocalVarNumber()
    * Void set_LocalVarNumber(Int32)
    * Int32 get_UniqueNumber()
    * Void set_UniqueNumber(Int32)
    * System.Collections.Generic.Dictionary`2[System.String,System.Int32] get_GlobalVariables()
    * Void set_GlobalVariables(System.Collections.Generic.Dictionary`2[System.String,System.Int32])
    * System.Collections.Generic.Dictionary`2[System.String,System.Int32] get_InstanceVariables()
    * Void set_InstanceVariables(System.Collections.Generic.Dictionary`2[System.String,System.Int32])
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.GMLCPPFunction] get_LegacyUsed()
    * Void set_LegacyUsed(System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.GMLCPPFunction])
    * GMAssetCompiler.GMLCode get_Code()
    * Void set_Code(GMAssetCompiler.GMLCode)
    * GMAssetCompiler.VMBuffer get_VMB()
    * Void set_VMB(GMAssetCompiler.VMBuffer)
    * Boolean get_ErrorFlag()
    * Void set_ErrorFlag(Boolean)
    * Boolean get_ContinueIllegal()
    * Void set_ContinueIllegal(Boolean)
    * Void CompileJS(GMAssetCompiler.GMAssets, GMAssetCompiler.GMLCode)
    * Void Error(System.String, GMAssetCompiler.GMLToken)
    * Void Warning(System.String, GMAssetCompiler.GMLToken)
    * GMAssetCompiler.GMLToken RewriteTree(GMAssetCompiler.GMLToken)
    * GMAssetCompiler.GMLToken OptimizeTree(GMAssetCompiler.GMLToken)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int64 OutputBase
    * System.Collections.Generic.Stack`1[System.Boolean] VariableExpressionStack
    * System.Collections.Generic.Stack`1[GMAssetCompiler.eVM_Type] TypeStack
    * System.Collections.Generic.Stack`1[GMAssetCompiler.VMLabel] LoopEnv
    * System.Collections.Generic.Stack`1[GMAssetCompiler.VMLabel] LoopEndEnv
    * System.Collections.Generic.Dictionary`2[System.Int32,System.Collections.Generic.List`1[System.Int64]] VarPatches
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.CPPLocalVar] CPPVars
    * System.Collections.Generic.Dictionary`2[System.String,System.Byte[]] CPPStrings
    * System.String FileName
    * System.Collections.Generic.List`1[System.String] UsedStrings
    * System.Collections.Generic.List`1[GMAssetCompiler.GMLCPPFunction] ScriptsUsed
    * Boolean IsScript
    * Boolean UsesArgs
    * Boolean UsesConcat
    * Boolean ForceInline
    * Boolean UsesConcatThisExpression
    * Int32 NumConcats
    * Int32 MaxNumConcats
    * System.String ReturnLabel
    * Boolean ReturnLabelUsed
    * GMAssetCompiler.GMLCPPFunction FuncSignature
    * System.Collections.Generic.Stack`1[GMAssetCompiler.CPPVarTracking] VarTracking
    * System.Collections.Generic.Stack`1[System.Int32] ReturnStack
    * System.Collections.Generic.List`1[System.Int32] ReturnValueUsed
    * Int32 NumberReturnValues
    * Boolean GenerateArgumentCount
    * System.Collections.Generic.Dictionary`2[System.String,System.Double] ConstantDefs
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.GMLCPPFunction] LocalLegacyUsed
    * System.Collections.Generic.List`1[System.Int32] ArgumentStoredTo
    * System.Collections.Generic.List`1[System.String] Strings
    * Int32 LocalVarNumber
    * Int32 UniqueNumber
    * System.Collections.Generic.Dictionary`2[System.String,System.Int32] GlobalVariables
    * System.Collections.Generic.Dictionary`2[System.String,System.Int32] InstanceVariables
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.GMLCPPFunction] LegacyUsed
    * GMAssetCompiler.GMLCode Code
    * GMAssetCompiler.VMBuffer VMB
    * Boolean ErrorFlag
    * Boolean ContinueIllegal
    * Int32 m_breakInhibitCount
    * Int32 VARIABLE_ARRAY_MAX_DIMENSION
# GMAssetCompiler.eType
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.eType eGMLT_Unknown
    * GMAssetCompiler.eType eGMLT_Bool
    * GMAssetCompiler.eType eGMLT_Var
    * GMAssetCompiler.eType eGMLT_Real
    * GMAssetCompiler.eType eGMLT_String
# GMAssetCompiler.DummyStream
  ## Members
    * Boolean get_CanRead()
    * Boolean get_CanSeek()
    * Boolean get_CanWrite()
    * Void Flush()
    * Int64 get_Length()
    * Int64 get_Position()
    * Void set_Position(Int64)
    * Int32 Read(Byte[], Int32, Int32)
    * Int64 Seek(Int64, System.IO.SeekOrigin)
    * Void SetLength(Int64)
    * Void Write(Byte[], Int32, Int32)
    * Boolean get_CanTimeout()
    * Int32 get_ReadTimeout()
    * Void set_ReadTimeout(Int32)
    * Int32 get_WriteTimeout()
    * Void set_WriteTimeout(Int32)
    * System.Threading.Tasks.Task CopyToAsync(System.IO.Stream)
    * System.Threading.Tasks.Task CopyToAsync(System.IO.Stream, Int32)
    * System.Threading.Tasks.Task CopyToAsync(System.IO.Stream, Int32, System.Threading.CancellationToken)
    * Void CopyTo(System.IO.Stream)
    * Void CopyTo(System.IO.Stream, Int32)
    * Void Close()
    * Void Dispose()
    * System.Threading.Tasks.Task FlushAsync()
    * System.Threading.Tasks.Task FlushAsync(System.Threading.CancellationToken)
    * System.IAsyncResult BeginRead(Byte[], Int32, Int32, System.AsyncCallback, System.Object)
    * Int32 EndRead(System.IAsyncResult)
    * System.Threading.Tasks.Task`1[System.Int32] ReadAsync(Byte[], Int32, Int32)
    * System.Threading.Tasks.Task`1[System.Int32] ReadAsync(Byte[], Int32, Int32, System.Threading.CancellationToken)
    * System.IAsyncResult BeginWrite(Byte[], Int32, Int32, System.AsyncCallback, System.Object)
    * Void EndWrite(System.IAsyncResult)
    * System.Threading.Tasks.Task WriteAsync(Byte[], Int32, Int32)
    * System.Threading.Tasks.Task WriteAsync(Byte[], Int32, Int32, System.Threading.CancellationToken)
    * Int32 ReadByte()
    * Void WriteByte(Byte)
    * System.Object GetLifetimeService()
    * System.Object InitializeLifetimeService()
    * System.Runtime.Remoting.ObjRef CreateObjRef(System.Type)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Boolean CanRead
    * Boolean CanSeek
    * Boolean CanWrite
    * Int64 Length
    * Int64 Position
    * Boolean CanTimeout
    * Int32 ReadTimeout
    * Int32 WriteTimeout
# GMAssetCompiler.GML2JavaScript
  ## Members
    * Void Error(System.String, GMAssetCompiler.GMLToken)
    * Void Compile(GMAssetCompiler.GMAssets, GMAssetCompiler.GMLCode, System.IO.TextWriter)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String ms_varPrefix
    * System.Collections.Generic.Dictionary`2[System.String,System.String] ms_globals
# GMAssetCompiler.eVM_InstructionBase
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.eVM_InstructionBase eVMB_Push
    * GMAssetCompiler.eVM_InstructionBase eVMB_Push_Local
    * GMAssetCompiler.eVM_InstructionBase eVMB_Push_Global
    * GMAssetCompiler.eVM_InstructionBase eVMB_Push_Builtin
    * GMAssetCompiler.eVM_InstructionBase eVMB_Push_Immediate
    * GMAssetCompiler.eVM_InstructionBase eVMB_Pop
    * GMAssetCompiler.eVM_InstructionBase eVMB_Dup
    * GMAssetCompiler.eVM_InstructionBase eVMB_Conv
    * GMAssetCompiler.eVM_InstructionBase eVMB_Mul
    * GMAssetCompiler.eVM_InstructionBase eVMB_Div
    * GMAssetCompiler.eVM_InstructionBase eVMB_Rem
    * GMAssetCompiler.eVM_InstructionBase eVMB_Mod
    * GMAssetCompiler.eVM_InstructionBase eVMB_Add
    * GMAssetCompiler.eVM_InstructionBase eVMB_Sub
    * GMAssetCompiler.eVM_InstructionBase eVMB_And
    * GMAssetCompiler.eVM_InstructionBase eVMB_Or
    * GMAssetCompiler.eVM_InstructionBase eVMB_Xor
    * GMAssetCompiler.eVM_InstructionBase eVMB_Neg
    * GMAssetCompiler.eVM_InstructionBase eVMB_Not
    * GMAssetCompiler.eVM_InstructionBase eVMB_Shl
    * GMAssetCompiler.eVM_InstructionBase eVMB_Shr
    * GMAssetCompiler.eVM_InstructionBase eVMB_Set
    * GMAssetCompiler.eVM_InstructionBase eVMB_Branch
    * GMAssetCompiler.eVM_InstructionBase eVMB_Btrue
    * GMAssetCompiler.eVM_InstructionBase eVMB_Bfalse
    * GMAssetCompiler.eVM_InstructionBase eVMB_Call
    * GMAssetCompiler.eVM_InstructionBase eVMB_Pushenv
    * GMAssetCompiler.eVM_InstructionBase eVMB_Popenv
    * GMAssetCompiler.eVM_InstructionBase eVMB_Ret
    * GMAssetCompiler.eVM_InstructionBase eVMB_Exit
    * GMAssetCompiler.eVM_InstructionBase eVMB_Popnull
    * GMAssetCompiler.eVM_InstructionBase eVMB_LastOne
# GMAssetCompiler.eVM_Instruction
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.eVM_Instruction kSingleArg
    * GMAssetCompiler.eVM_Instruction kDoubleArg
    * GMAssetCompiler.eVM_Instruction kParam
    * GMAssetCompiler.eVM_Instruction kBranchTarget
    * GMAssetCompiler.eVM_Instruction kVAR_not_array
    * GMAssetCompiler.eVM_Instruction kVAR_objind_over
    * GMAssetCompiler.eVM_Instruction kVAR_objind_embed
    * GMAssetCompiler.eVM_Instruction kVAR_not_configurable
    * GMAssetCompiler.eVM_Instruction kVARIND_mask
    * GMAssetCompiler.eVM_Instruction eVMI_PUSH
    * GMAssetCompiler.eVM_Instruction eVMI_PUSHV
    * GMAssetCompiler.eVM_Instruction eVMI_PUSH_LOCAL
    * GMAssetCompiler.eVM_Instruction eVMI_PUSH_GLOBAL
    * GMAssetCompiler.eVM_Instruction eVMI_PUSH_BUILTIN
    * GMAssetCompiler.eVM_Instruction eVMI_PUSH_IMMEDIATE
    * GMAssetCompiler.eVM_Instruction eVMI_POP
    * GMAssetCompiler.eVM_Instruction eVMI_POPV
    * GMAssetCompiler.eVM_Instruction eVMI_DUP
    * GMAssetCompiler.eVM_Instruction eVMI_CONV
    * GMAssetCompiler.eVM_Instruction eVMI_MUL
    * GMAssetCompiler.eVM_Instruction eVMI_DIV
    * GMAssetCompiler.eVM_Instruction eVMI_REM
    * GMAssetCompiler.eVM_Instruction eVMI_MOD
    * GMAssetCompiler.eVM_Instruction eVMI_ADD
    * GMAssetCompiler.eVM_Instruction eVMI_SUB
    * GMAssetCompiler.eVM_Instruction eVMI_AND
    * GMAssetCompiler.eVM_Instruction eVMI_OR
    * GMAssetCompiler.eVM_Instruction eVMI_XOR
    * GMAssetCompiler.eVM_Instruction eVMI_NEG
    * GMAssetCompiler.eVM_Instruction eVMI_NOT
    * GMAssetCompiler.eVM_Instruction eVMI_SHL
    * GMAssetCompiler.eVM_Instruction eVMI_SHR
    * GMAssetCompiler.eVM_Instruction eVMI_SET
    * GMAssetCompiler.eVM_Instruction eVMI_BRANCH
    * GMAssetCompiler.eVM_Instruction eVMI_BTRUE
    * GMAssetCompiler.eVM_Instruction eVMI_BFALSE
    * GMAssetCompiler.eVM_Instruction eVMI_CALL
    * GMAssetCompiler.eVM_Instruction eVMI_CALLV
    * GMAssetCompiler.eVM_Instruction eVMI_PUSHENV
    * GMAssetCompiler.eVM_Instruction eVMI_POPENV
    * GMAssetCompiler.eVM_Instruction eVMI_RET
    * GMAssetCompiler.eVM_Instruction eVMI_EXIT
    * GMAssetCompiler.eVM_Instruction eVMI_POPNULL
    * GMAssetCompiler.eVM_Instruction eVMI_BREAK
# GMAssetCompiler.eVM_ConditionCode
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.eVM_ConditionCode eVMCC_NONE
    * GMAssetCompiler.eVM_ConditionCode eVMCC_LT
    * GMAssetCompiler.eVM_ConditionCode eVMCC_LE
    * GMAssetCompiler.eVM_ConditionCode eVMCC_EQ
    * GMAssetCompiler.eVM_ConditionCode eVMCC_NE
    * GMAssetCompiler.eVM_ConditionCode eVMCC_GE
    * GMAssetCompiler.eVM_ConditionCode eVMCC_GT
# GMAssetCompiler.eVM_Type
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.eVM_Type eVMT_Error
    * GMAssetCompiler.eVM_Type eVMT_Double
    * GMAssetCompiler.eVM_Type eVMT_Float
    * GMAssetCompiler.eVM_Type eVMT_Int
    * GMAssetCompiler.eVM_Type eVMT_Long
    * GMAssetCompiler.eVM_Type eVMT_Bool
    * GMAssetCompiler.eVM_Type eVMT_Variable
    * GMAssetCompiler.eVM_Type eVMT_String
    * GMAssetCompiler.eVM_Type eVMT_Instance
# GMAssetCompiler.VMBuffer
  ## Members
    * System.IO.MemoryStream get_Buffer()
    * Void set_Buffer(System.IO.MemoryStream)
    * Int32 GetInt(Int32)
    * Void SetInt(Int32, Int32)
    * Void Add(Int32[])
    * Int32 EncodeArgDouble(Int32, Int32)
    * Int32 EncodeInstructionArg(Int32, Int32)
    * Int32 EncodeInstructionArgCond(Int32, Int32, Int32)
    * Int32 EncodeInstructionBranch(Int32, Int32)
    * Int32 GetInstruction(Int32)
    * Int32 GetArg(Int32)
    * Int32 GetBranch(Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.MemoryStream Buffer
# GMAssetCompiler.VMLabel
  ## Members
    * GMAssetCompiler.VMBuffer get_VMB()
    * Void set_VMB(GMAssetCompiler.VMBuffer)
    * System.String get_Label()
    * Void set_Label(System.String)
    * Int64 get_Address()
    * Void set_Address(Int64)
    * System.Collections.Generic.List`1[System.Int32] get_Patches()
    * Void set_Patches(System.Collections.Generic.List`1[System.Int32])
    * Boolean get_Marked()
    * Void set_Marked(Boolean)
    * Int32 get_BreakCount()
    * Void set_BreakCount(Int32)
    * Void Mark(Int64)
    * Void Patch()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String, GMAssetCompiler.VMBuffer)
    * GMAssetCompiler.VMBuffer VMB
    * System.String Label
    * Int64 Address
    * System.Collections.Generic.List`1[System.Int32] Patches
    * Boolean Marked
    * Int32 BreakCount
# GMAssetCompiler.GML2VM
  ## Members
    * Int64 get_OutputBase()
    * Void set_OutputBase(Int64)
    * System.Collections.Generic.Stack`1[System.Boolean] get_VariableExpressionStack()
    * Void set_VariableExpressionStack(System.Collections.Generic.Stack`1[System.Boolean])
    * System.Collections.Generic.Stack`1[GMAssetCompiler.eVM_Type] get_TypeStack()
    * Void set_TypeStack(System.Collections.Generic.Stack`1[GMAssetCompiler.eVM_Type])
    * System.Collections.Generic.Stack`1[GMAssetCompiler.VMLabel] get_LoopEnv()
    * Void set_LoopEnv(System.Collections.Generic.Stack`1[GMAssetCompiler.VMLabel])
    * System.Collections.Generic.Stack`1[GMAssetCompiler.VMLabel] get_LoopEndEnv()
    * Void set_LoopEndEnv(System.Collections.Generic.Stack`1[GMAssetCompiler.VMLabel])
    * System.Collections.Generic.List`1[System.Int32] get_DebugInfo()
    * Void set_DebugInfo(System.Collections.Generic.List`1[System.Int32])
    * Int32 get_LastDebugInfo()
    * Void set_LastDebugInfo(Int32)
    * System.Collections.Generic.List`1[System.String] get_Strings()
    * Void set_Strings(System.Collections.Generic.List`1[System.String])
    * System.Collections.Generic.List`1[System.Int64] get_StringPatches()
    * Void set_StringPatches(System.Collections.Generic.List`1[System.Int64])
    * System.Collections.Generic.Dictionary`2[System.Int32,System.Collections.Generic.List`1[GMAssetCompiler.GML2VM+SVarPatchInfo]] get_VarPatches()
    * Void set_VarPatches(System.Collections.Generic.Dictionary`2[System.Int32,System.Collections.Generic.List`1[GMAssetCompiler.GML2VM+SVarPatchInfo]])
    * System.Collections.Generic.Dictionary`2[System.Int32,System.Collections.Generic.List`1[System.Int64]] get_FuncPatches()
    * Void set_FuncPatches(System.Collections.Generic.Dictionary`2[System.Int32,System.Collections.Generic.List`1[System.Int64]])
    * System.Collections.Generic.List`1[System.Int32] get_ObjectStringEntry()
    * Void set_ObjectStringEntry(System.Collections.Generic.List`1[System.Int32])
    * System.Collections.Generic.List`1[System.Int64] get_ObjectPatches()
    * Void set_ObjectPatches(System.Collections.Generic.List`1[System.Int64])
    * Boolean CompareTokenTree(GMAssetCompiler.GMLToken, GMAssetCompiler.GMLToken)
    * Int32 DisasmOne(GMAssetCompiler.VMBuffer, Int32, System.IO.TextWriter)
    * Void Disasm(System.IO.TextWriter)
    * Void Compile(GMAssetCompiler.GMAssets, GMAssetCompiler.GMLCode)
    * Void CompileJS(GMAssetCompiler.GMAssets, GMAssetCompiler.GMLCode)
    * GMAssetCompiler.GMLCode get_Code()
    * Void set_Code(GMAssetCompiler.GMLCode)
    * GMAssetCompiler.VMBuffer get_VMB()
    * Void set_VMB(GMAssetCompiler.VMBuffer)
    * Boolean get_ErrorFlag()
    * Void set_ErrorFlag(Boolean)
    * Boolean get_ContinueIllegal()
    * Void set_ContinueIllegal(Boolean)
    * Void Error(System.String, GMAssetCompiler.GMLToken)
    * Void Warning(System.String, GMAssetCompiler.GMLToken)
    * GMAssetCompiler.GMLToken RewriteTree(GMAssetCompiler.GMLToken)
    * GMAssetCompiler.GMLToken OptimizeTree(GMAssetCompiler.GMLToken)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int64 OutputBase
    * System.Collections.Generic.Stack`1[System.Boolean] VariableExpressionStack
    * System.Collections.Generic.Stack`1[GMAssetCompiler.eVM_Type] TypeStack
    * System.Collections.Generic.Stack`1[GMAssetCompiler.VMLabel] LoopEnv
    * System.Collections.Generic.Stack`1[GMAssetCompiler.VMLabel] LoopEndEnv
    * System.Collections.Generic.List`1[System.Int32] DebugInfo
    * Int32 LastDebugInfo
    * System.Collections.Generic.List`1[System.String] Strings
    * System.Collections.Generic.List`1[System.Int64] StringPatches
    * System.Collections.Generic.Dictionary`2[System.Int32,System.Collections.Generic.List`1[GMAssetCompiler.GML2VM+SVarPatchInfo]] VarPatches
    * System.Collections.Generic.Dictionary`2[System.Int32,System.Collections.Generic.List`1[System.Int64]] FuncPatches
    * System.Collections.Generic.List`1[System.Int32] ObjectStringEntry
    * System.Collections.Generic.List`1[System.Int64] ObjectPatches
    * GMAssetCompiler.GMLCode Code
    * GMAssetCompiler.VMBuffer VMB
    * Boolean ErrorFlag
    * Boolean ContinueIllegal
    * System.Collections.Generic.Dictionary`2[GMAssetCompiler.GML2VM+SPatchKey,System.Int32] var_names
    * GMAssetCompiler.GML2VM+EVariableType
    * GMAssetCompiler.GML2VM+SVarPatchInfo
    * GMAssetCompiler.GML2VM+SPatchKey
# GMAssetCompiler.GML2VM+EVariableType
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * EVariableType EGLOBAL
    * EVariableType EINSTANCE
    * EVariableType ELOCAL
    * EVariableType EUNKNOWN
# GMAssetCompiler.GML2VM+SVarPatchInfo
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor(Int64, EVariableType)
    * Int64 location
    * EVariableType type
# GMAssetCompiler.GML2VM+SPatchKey
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor(Int32, EVariableType, Int32)
    * Int32 var_id
    * EVariableType var_type
    * Int32 code_number
# GMAssetCompiler.eGMLCodeType
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.eGMLCodeType eScript
    * GMAssetCompiler.eGMLCodeType eEvent
    * GMAssetCompiler.eGMLCodeType eRoomCreate
    * GMAssetCompiler.eGMLCodeType eRoomInstanceCreate
    * GMAssetCompiler.eGMLCodeType eTrigger
    * GMAssetCompiler.eGMLCodeType eConstant
    * GMAssetCompiler.eGMLCodeType eExpression
# GMAssetCompiler.SubFunctionLocalInfo
  ## Members
    * System.String get_Decorated()
    * System.String get_Undecorated()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.YYJSLocalEntry, System.Collections.Generic.List`1[System.String])
    * System.String Decorated
    * System.String Undecorated
# GMAssetCompiler.SubFunctionInfo
  ## Members
    * System.String get_Decorated()
    * System.String get_Undecorated()
    * Int64 get_Offset()
    * System.Collections.Generic.List`1[System.String] get_Args()
    * System.Collections.Generic.List`1[GMAssetCompiler.SubFunctionLocalInfo] get_Locals()
    * System.Collections.Generic.List`1[GMAssetCompiler.SubFunctionLocalInfo] get_InstanceVars()
    * Int32 get_NumArguments()
    * Void set_NumArguments(Int32)
    * Int32 get_NumLocals()
    * Void set_NumLocals(Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.YYJSScriptEntry, System.Collections.Generic.List`1[System.String])
    * System.String Decorated
    * System.String Undecorated
    * Int64 Offset
    * System.Collections.Generic.List`1[System.String] Args
    * System.Collections.Generic.List`1[GMAssetCompiler.SubFunctionLocalInfo] Locals
    * System.Collections.Generic.List`1[GMAssetCompiler.SubFunctionLocalInfo] InstanceVars
    * Int32 NumArguments
    * Int32 NumLocals
# GMAssetCompiler.GMLCode
  ## Members
    * GMAssetCompiler.eGMLCodeType get_Type()
    * Void set_Type(GMAssetCompiler.eGMLCodeType)
    * System.String get_SourceFileName()
    * Void set_SourceFileName(System.String)
    * System.String get_Name()
    * Void set_Name(System.String)
    * System.String get_Code()
    * Void set_Code(System.String)
    * GMAssetCompiler.eScriptKind get_Kind()
    * Void set_Kind(GMAssetCompiler.eScriptKind)
    * Int32 get_NumArguments()
    * Void set_NumArguments(Int32)
    * Int32 get_ArgumentMask()
    * Void set_ArgumentMask(Int32)
    * GMAssetCompiler.GMLToken get_Token()
    * Void set_Token(GMAssetCompiler.GMLToken)
    * System.Collections.Generic.List`1[GMAssetCompiler.GMLError] get_Errors()
    * Void set_Errors(System.Collections.Generic.List`1[GMAssetCompiler.GMLError])
    * System.Collections.Generic.Dictionary`2[System.String,System.String] get_LocalVars()
    * Void set_LocalVars(System.Collections.Generic.Dictionary`2[System.String,System.String])
    * System.Collections.Generic.List`1[System.Int32] get_NewLines()
    * Void set_NewLines(System.Collections.Generic.List`1[System.Int32])
    * System.Collections.Generic.List`1[GMAssetCompiler.GMLToken] get_Pragmas()
    * Void set_Pragmas(System.Collections.Generic.List`1[GMAssetCompiler.GMLToken])
    * IntPtr get_pJavaScript()
    * Void set_pJavaScript(IntPtr)
    * System.Collections.Generic.List`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.SubFunctionInfo]] get_SubFunctions()
    * Void set_SubFunctions(System.Collections.Generic.List`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.SubFunctionInfo]])
    * Int32 get_CodeIndex()
    * Void set_CodeIndex(Int32)
    * Int32 GetLineNumber(Int32)
    * Void CollectStatsVariable(GMAssetCompiler.GMLToken)
    * Void CollectStatsDot(GMAssetCompiler.GMLToken)
    * GMAssetCompiler.GMLToken CollectStats(GMAssetCompiler.GMLToken)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.String, System.String, GMAssetCompiler.eScriptKind, GMAssetCompiler.eGMLCodeType, Boolean)
    * GMAssetCompiler.eGMLCodeType Type
    * System.String SourceFileName
    * System.String Name
    * System.String Code
    * GMAssetCompiler.eScriptKind Kind
    * Int32 NumArguments
    * Int32 ArgumentMask
    * GMAssetCompiler.GMLToken Token
    * System.Collections.Generic.List`1[GMAssetCompiler.GMLError] Errors
    * System.Collections.Generic.Dictionary`2[System.String,System.String] LocalVars
    * System.Collections.Generic.List`1[System.Int32] NewLines
    * System.Collections.Generic.List`1[GMAssetCompiler.GMLToken] Pragmas
    * IntPtr pJavaScript
    * System.Collections.Generic.List`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.SubFunctionInfo]] SubFunctions
    * Int32 CodeIndex
    * System.Collections.Generic.Dictionary`2[System.String,System.Collections.Generic.List`1[System.Collections.Generic.KeyValuePair`2[GMAssetCompiler.GMLCode,GMAssetCompiler.GMLToken]]] FunctionVarAsArray
    * System.Collections.Generic.Dictionary`2[System.String,System.Collections.Generic.List`1[System.Collections.Generic.KeyValuePair`2[GMAssetCompiler.GMLCode,GMAssetCompiler.GMLToken]]] FunctionVarAsScalar
    * Int32 index
    * System.Collections.Generic.Dictionary`2[System.String,System.Int32] GlobalVars
    * Int32 globalIndex
    * System.Collections.Generic.Dictionary`2[System.String,System.Int32] InstanceVars
    * Int32 instanceIndex
    * System.Collections.Generic.Dictionary`2[System.String,System.Collections.Generic.List`1[System.Collections.Generic.KeyValuePair`2[GMAssetCompiler.GMLCode,GMAssetCompiler.GMLToken]]] VarAsArray
    * System.Collections.Generic.Dictionary`2[System.String,System.Collections.Generic.List`1[System.Collections.Generic.KeyValuePair`2[GMAssetCompiler.GMLCode,GMAssetCompiler.GMLToken]]] VarAsScalar
# GMAssetCompiler.Output.GMLParseTreeRewriter
  ## Members
    * GMAssetCompiler.GMLToken RewriteProgram(GMAssetCompiler.GMLToken)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.Stack`1[System.Boolean] LValue
# GMAssetCompiler.Output.GMLCollectStats
  ## Members
    * GMAssetCompiler.GMLCode get_Code()
    * Void set_Code(GMAssetCompiler.GMLCode)
    * GMAssetCompiler.GMLToken RewriteProgram(GMAssetCompiler.GMLToken)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMLCode)
    * GMAssetCompiler.GMLCode Code
    * System.Collections.Generic.Stack`1[System.Boolean] LValue
# GMAssetCompiler.eAssetType
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.eAssetType eAT_None
    * GMAssetCompiler.eAssetType eAT_Object
    * GMAssetCompiler.eAssetType eAT_Sprite
    * GMAssetCompiler.eAssetType eAT_Sound
    * GMAssetCompiler.eAssetType eAT_Room
    * GMAssetCompiler.eAssetType eAT_Background
    * GMAssetCompiler.eAssetType eAT_Path
    * GMAssetCompiler.eAssetType eAT_Script
    * GMAssetCompiler.eAssetType eAT_Font
    * GMAssetCompiler.eAssetType eAT_Timeline
    * GMAssetCompiler.eAssetType eAT_Tiles
# GMAssetCompiler.eToken
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.eToken eEOF
    * GMAssetCompiler.eToken eError
    * GMAssetCompiler.eToken eName
    * GMAssetCompiler.eToken eNumber
    * GMAssetCompiler.eToken eString
    * GMAssetCompiler.eToken eConstant
    * GMAssetCompiler.eToken eFunction
    * GMAssetCompiler.eToken eVariable
    * GMAssetCompiler.eToken eVariableSimple
    * GMAssetCompiler.eToken eGlobal
    * GMAssetCompiler.eToken eBegin
    * GMAssetCompiler.eToken eEnd
    * GMAssetCompiler.eToken eIf
    * GMAssetCompiler.eToken eThen
    * GMAssetCompiler.eToken eElse
    * GMAssetCompiler.eToken eWhile
    * GMAssetCompiler.eToken eDo
    * GMAssetCompiler.eToken eFor
    * GMAssetCompiler.eToken eUntil
    * GMAssetCompiler.eToken eRepeat
    * GMAssetCompiler.eToken eExit
    * GMAssetCompiler.eToken eBreak
    * GMAssetCompiler.eToken eContinue
    * GMAssetCompiler.eToken eWith
    * GMAssetCompiler.eToken eReturn
    * GMAssetCompiler.eToken eSwitch
    * GMAssetCompiler.eToken eCase
    * GMAssetCompiler.eToken eDefault
    * GMAssetCompiler.eToken eVar
    * GMAssetCompiler.eToken eGlobalVar
    * GMAssetCompiler.eToken eCaseConstant
    * GMAssetCompiler.eToken eAssign
    * GMAssetCompiler.eToken eAssignPlus
    * GMAssetCompiler.eToken eAssignMinus
    * GMAssetCompiler.eToken eAssignTimes
    * GMAssetCompiler.eToken eAssignDivide
    * GMAssetCompiler.eToken eOpen
    * GMAssetCompiler.eToken eClose
    * GMAssetCompiler.eToken eSepStatement
    * GMAssetCompiler.eToken eSepArgument
    * GMAssetCompiler.eToken eArrayOpen
    * GMAssetCompiler.eToken eArrayClose
    * GMAssetCompiler.eToken eDot
    * GMAssetCompiler.eToken eLabel
    * GMAssetCompiler.eToken eAssignOr
    * GMAssetCompiler.eToken eAssignAnd
    * GMAssetCompiler.eToken eAssignXor
    * GMAssetCompiler.eToken eAssignMod
    * GMAssetCompiler.eToken eAnd
    * GMAssetCompiler.eToken eOr
    * GMAssetCompiler.eToken eNot
    * GMAssetCompiler.eToken eLess
    * GMAssetCompiler.eToken eLessEqual
    * GMAssetCompiler.eToken eEqual
    * GMAssetCompiler.eToken eNotEqual
    * GMAssetCompiler.eToken eGreaterEqual
    * GMAssetCompiler.eToken eGreater
    * GMAssetCompiler.eToken ePlus
    * GMAssetCompiler.eToken eMinus
    * GMAssetCompiler.eToken eTime
    * GMAssetCompiler.eToken eDivide
    * GMAssetCompiler.eToken eDiv
    * GMAssetCompiler.eToken eMod
    * GMAssetCompiler.eToken eXor
    * GMAssetCompiler.eToken eBitOr
    * GMAssetCompiler.eToken eBitAnd
    * GMAssetCompiler.eToken eBitXor
    * GMAssetCompiler.eToken eBitNegate
    * GMAssetCompiler.eToken eBitShiftLeft
    * GMAssetCompiler.eToken eBitShiftRight
    * GMAssetCompiler.eToken ePlusPlus
    * GMAssetCompiler.eToken eMinusMinus
    * GMAssetCompiler.eToken eEnum
    * GMAssetCompiler.eToken eStruct
    * GMAssetCompiler.eToken eBlock
    * GMAssetCompiler.eToken eUnary
    * GMAssetCompiler.eToken eBinary
    * GMAssetCompiler.eToken ePre
    * GMAssetCompiler.eToken ePost
    * GMAssetCompiler.eToken eMapArrayOpen
    * GMAssetCompiler.eToken eListArrayOpen
    * GMAssetCompiler.eToken eGridArrayOpen
    * GMAssetCompiler.eToken eByteArrayOpen
    * GMAssetCompiler.eToken eWordArrayOpen
    * GMAssetCompiler.eToken eDwordArrayOpen
    * GMAssetCompiler.eToken eUnsignedByteArrayOpen
    * GMAssetCompiler.eToken eUnsignedWordArrayOpen
    * GMAssetCompiler.eToken eUnsignedDwordArrayOpen
    * GMAssetCompiler.eToken eFloatArrayOpen
    * GMAssetCompiler.eToken eDoubleArrayOpen
    * GMAssetCompiler.eToken eBaseArrayOpen
# GMAssetCompiler.eKind
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.eKind eNone
    * GMAssetCompiler.eKind eNumber
    * GMAssetCompiler.eKind eString
    * GMAssetCompiler.eKind eConstant
# GMAssetCompiler.GMLValue
  ## Members
    * GMAssetCompiler.eKind get_Kind()
    * Void set_Kind(GMAssetCompiler.eKind)
    * Double get_ValueI()
    * Void set_ValueI(Double)
    * System.String get_ValueS()
    * Void set_ValueS(System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(Double)
    * Void .ctor(System.String)
    * Void .ctor(GMAssetCompiler.GMLValue)
    * GMAssetCompiler.eKind Kind
    * Double ValueI
    * System.String ValueS
# GMAssetCompiler.GMLToken
  ## Members
    * GMAssetCompiler.eToken get_Token()
    * Void set_Token(GMAssetCompiler.eToken)
    * Int32 get_Index()
    * Void set_Index(Int32)
    * System.String get_Text()
    * Void set_Text(System.String)
    * GMAssetCompiler.eVM_Type get_Type()
    * Void set_Type(GMAssetCompiler.eVM_Type)
    * GMAssetCompiler.eVM_Type get_OriginalType()
    * Void set_OriginalType(GMAssetCompiler.eVM_Type)
    * Int32 get_Id()
    * Void set_Id(Int32)
    * GMAssetCompiler.GMLValue get_Value()
    * Void set_Value(GMAssetCompiler.GMLValue)
    * System.Object get_Object()
    * Void set_Object(System.Object)
    * System.Collections.Generic.List`1[GMAssetCompiler.GMLToken] get_Children()
    * Void set_Children(System.Collections.Generic.List`1[GMAssetCompiler.GMLToken])
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.eToken, Int32, System.String)
    * Void .ctor(GMAssetCompiler.eToken, GMAssetCompiler.GMLToken, Int32)
    * Void .ctor(GMAssetCompiler.eToken, GMAssetCompiler.GMLToken, Int32, GMAssetCompiler.GMLValue)
    * Void .ctor(GMAssetCompiler.GMLToken)
    * GMAssetCompiler.eToken Token
    * Int32 Index
    * System.String Text
    * GMAssetCompiler.eVM_Type Type
    * GMAssetCompiler.eVM_Type OriginalType
    * Int32 Id
    * GMAssetCompiler.GMLValue Value
    * System.Object Object
    * System.Collections.Generic.List`1[GMAssetCompiler.GMLToken] Children
# GMAssetCompiler.eErrorKind
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.eErrorKind Warning
    * GMAssetCompiler.eErrorKind Warning_Unclosed_Comment
    * GMAssetCompiler.eErrorKind Error
# GMAssetCompiler.GMLError
  ## Members
    * GMAssetCompiler.eErrorKind get_Kind()
    * Void set_Kind(GMAssetCompiler.eErrorKind)
    * System.String get_Error()
    * Void set_Error(System.String)
    * System.Collections.Generic.List`1[System.Object] get_Params()
    * Void set_Params(System.Collections.Generic.List`1[System.Object])
    * GMAssetCompiler.GMLToken get_Token()
    * Void set_Token(GMAssetCompiler.GMLToken)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.eErrorKind, System.String, GMAssetCompiler.GMLToken, System.Object[])
    * GMAssetCompiler.eErrorKind Kind
    * System.String Error
    * System.Collections.Generic.List`1[System.Object] Params
    * GMAssetCompiler.GMLToken Token
# GMAssetCompiler.GMLFunction
  ## Members
    * System.String get_Name()
    * Void set_Name(System.String)
    * Int32 get_Id()
    * Void set_Id(Int32)
    * Int32 get_NumArgs7()
    * Void set_NumArgs7(Int32)
    * Int32 get_NumArgs8()
    * Void set_NumArgs8(Int32)
    * Boolean get_Pro()
    * Void set_Pro(Boolean)
    * Boolean get_InstanceFirstParam()
    * Void set_InstanceFirstParam(Boolean)
    * Boolean get_OtherSecondParam()
    * Void set_OtherSecondParam(Boolean)
    * Int32 get_Count()
    * Void set_Count(Int32)
    * GMAssetCompiler.Output.FunctionClassification get_Classification()
    * Void set_Classification(GMAssetCompiler.Output.FunctionClassification)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * Int32 Id
    * Int32 NumArgs7
    * Int32 NumArgs8
    * Boolean Pro
    * Boolean InstanceFirstParam
    * Boolean OtherSecondParam
    * Int32 Count
    * GMAssetCompiler.Output.FunctionClassification Classification
# GMAssetCompiler.GMLVariable
  ## Members
    * System.String get_Name()
    * Void set_Name(System.String)
    * System.String get_setFunction()
    * Void set_setFunction(System.String)
    * System.String get_getFunction()
    * Void set_getFunction(System.String)
    * Int32 get_Id()
    * Void set_Id(Int32)
    * Boolean get_Get()
    * Void set_Get(Boolean)
    * Boolean get_Set()
    * Void set_Set(Boolean)
    * Boolean get_Pro()
    * Void set_Pro(Boolean)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String setFunction
    * System.String getFunction
    * Int32 Id
    * Boolean Get
    * Boolean Set
    * Boolean Pro
# GMAssetCompiler.FunctionRecord
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 extension
    * Int32 include
    * Int32 function
# GMAssetCompiler.GMLCompile
  ## Members
    * Void Check(System.String, GMAssetCompiler.eToken)
    * Void Test()
    * Void Error(System.String, System.String, GMAssetCompiler.GMLToken)
    * Void Warning(System.String, System.String, GMAssetCompiler.GMLToken)
    * Void Code_Init()
    * Int32 Find[T](System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,T]], System.String)
    * Void AddNameIndex[T](System.Collections.Generic.Dictionary`2[System.String,System.Int32], System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,T]])
    * Int32 FindTriggerConstName(System.Collections.Generic.IList`1[GMAssetCompiler.GMTrigger], System.String)
    * Int32 PackFunctionID(System.String, Int32, Int32, Int32)
    * Void UnpackFunctionID(Int32, Int32 ByRef, Int32 ByRef, Int32 ByRef)
    * Int32 Code_Function_Find(System.String, System.String ByRef)
    * Int32 Code_Variable_Find(System.String)
    * Void OptimizeOrdCall(GMAssetCompiler.GMLToken ByRef)
    * Void OptimizeChrCall(GMAssetCompiler.GMLToken ByRef)
    * Void OptimizeFunction(GMAssetCompiler.GMLToken ByRef)
    * Void OptimizeEnumConstants(GMAssetCompiler.GMLToken ByRef)
    * Void OptimizeIf(GMAssetCompiler.GMLToken ByRef)
    * GMAssetCompiler.GMLToken OptimizeTree(GMAssetCompiler.GMLToken)
    * Boolean CompileConstants(GMAssetCompiler.GMAssets)
    * GMAssetCompiler.GMLToken Compile(GMAssetCompiler.GMAssets, System.String, System.String, System.Collections.Generic.List`1[GMAssetCompiler.GMLError] ByRef, Boolean, Boolean)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.Dictionary`2[System.String,System.Double] ms_constants
    * System.Collections.Generic.Dictionary`2[System.String,System.Int32] ms_ConstantCount
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.GMLFunction] ms_funcs
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.GMLVariable] ms_builtins
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.GMLVariable] ms_builtinsArray
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.GMLVariable] ms_builtinsLocal
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.GMLVariable] ms_builtinsLocalArray
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.GMLCode] ms_codeConstants
    * System.Collections.Generic.Dictionary`2[System.String,System.Int32] ms_resourceIndex
    * System.Collections.Generic.Dictionary`2[System.Int32,System.Collections.Generic.Dictionary`2[System.Int32,System.Collections.Generic.Dictionary`2[System.Int32,System.Int32]]] ms_functionDictionary
    * System.Collections.Generic.List`1[GMAssetCompiler.GMLToken] ms_pragmas
    * GMAssetCompiler.FunctionRecord[] ms_functionRecords
    * Int32 ms_id
    * System.String ms_script
    * System.Collections.Generic.Dictionary`2[System.String,System.String] ms_localvars
    * System.Collections.Generic.Dictionary`2[System.String,System.Collections.Generic.Dictionary`2[System.String,System.Int32]] ms_enums
    * System.String ms_scriptName
    * Int32 ms_argumentMaxUsed
    * Int32 ms_argumentMask
    * Int32 OBJECT_SELF
    * Int32 OBJECT_OTHER
    * Int32 OBJECT_ALL
    * Int32 OBJECT_NOONE
    * Int32 OBJECT_GLOBAL
    * Int32 OBJECT_LOCAL
    * Int32 OBJECT_NOTSPECIFIED
    * Int32 OBJECT_INTERNAL
    * Int32 OS_LLVM_CONSTANT_BASE
    * Int32 AUDIO_FALLOFF_NONE
    * Int32 AUDIO_FALLOFF_INVERSE_DISTANCE
    * Int32 AUDIO_FALLOFF_INVERSE_DISTANCE_CLAMPED
    * Int32 AUDIO_FALLOFF_LINEAR_DISTANCE
    * Int32 AUDIO_FALLOFF_LINEAR_DISTANCE_CLAMPED
    * Int32 AUDIO_FALLOFF_EXPONENT_DISTANCE
    * Int32 AUDIO_FALLOFF_EXPONENT_DISTANCE_CLAMPED
# GMAssetCompiler.Output.GMLNewArrayAccessors
  ## Members
    * GMAssetCompiler.GMLToken RewriteProgram(GMAssetCompiler.GMLToken)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.Stack`1[System.Boolean] LValue
# GMAssetCompiler.Output.GMLNewArrayAccessors+ArrayAccessorInfo
  ## Members
    * System.String get_LValFunc()
    * Void set_LValFunc(System.String)
    * Int32 get_LValFuncId()
    * Void set_LValFuncId(Int32)
    * System.String get_LValPreFunc()
    * Void set_LValPreFunc(System.String)
    * Int32 get_LValPreFuncId()
    * Void set_LValPreFuncId(Int32)
    * System.String get_LValPostFunc()
    * Void set_LValPostFunc(System.String)
    * Int32 get_LValPostFuncId()
    * Void set_LValPostFuncId(Int32)
    * System.String get_RValFunc()
    * Void set_RValFunc(System.String)
    * Int32 get_RValFuncId()
    * Void set_RValFuncId(Int32)
    * Int32 get_NumDimensions()
    * Void set_NumDimensions(Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String, System.String, System.String, System.String, Int32)
    * System.String LValFunc
    * Int32 LValFuncId
    * System.String LValPreFunc
    * Int32 LValPreFuncId
    * System.String LValPostFunc
    * Int32 LValPostFuncId
    * System.String RValFunc
    * Int32 RValFuncId
    * Int32 NumDimensions
# GMAssetCompiler.HTML5Saver
  ## Members
    * GMAssetCompiler.GMAssets get_Assets()
    * System.String EnsureValidId(System.String)
    * Void Save(GMAssetCompiler.GMAssets, System.String)
    * Void GetFiles(System.String, System.String[], System.Collections.Generic.List`1[System.String])
    * System.String Extension_NewName(Int32)
    * System.String GetEventName(Int32, Int32)
    * Void Save(GMAssetCompiler.GMAssets, System.IO.TextWriter)
    * System.String GetKeyBoardEvent(Int32)
    * System.String GetJSEventName(Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * GMAssetCompiler.GMAssets Assets
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.GMLCode] ms_codeToCompile
    * System.Collections.Generic.List`1[System.String] ms_obfuscateKeywords
# GMAssetCompiler.HTML5Saver+WriteDelegateKVP`1[T]
  ## Members
    * Void Invoke(System.Collections.Generic.KeyValuePair`2[System.String,T], System.IO.TextWriter, Int32)
    * System.IAsyncResult BeginInvoke(System.Collections.Generic.KeyValuePair`2[System.String,T], System.IO.TextWriter, Int32, System.AsyncCallback, System.Object)
    * Void EndInvoke(System.IAsyncResult)
    * Void GetObjectData(System.Runtime.Serialization.SerializationInfo, System.Runtime.Serialization.StreamingContext)
    * Boolean Equals(System.Object)
    * System.Delegate[] GetInvocationList()
    * Int32 GetHashCode()
    * System.Object DynamicInvoke(System.Object[])
    * System.Reflection.MethodInfo get_Method()
    * System.Object get_Target()
    * System.Object Clone()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor(System.Object, IntPtr)
    * System.Reflection.MethodInfo Method
    * System.Object Target
# GMAssetCompiler.HTML5Saver+WriteDelegate`1[T]
  ## Members
    * Void Invoke(T, System.IO.TextWriter, Int32)
    * System.IAsyncResult BeginInvoke(T, System.IO.TextWriter, Int32, System.AsyncCallback, System.Object)
    * Void EndInvoke(System.IAsyncResult)
    * Void GetObjectData(System.Runtime.Serialization.SerializationInfo, System.Runtime.Serialization.StreamingContext)
    * Boolean Equals(System.Object)
    * System.Delegate[] GetInvocationList()
    * Int32 GetHashCode()
    * System.Object DynamicInvoke(System.Object[])
    * System.Reflection.MethodInfo get_Method()
    * System.Object get_Target()
    * System.Object Clone()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor(System.Object, IntPtr)
    * System.Reflection.MethodInfo Method
    * System.Object Target
# GMAssetCompiler.HTML5Saver+Codepage
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * Codepage ANSI_CHARSET
    * Codepage DEFAULT_CHARSET
    * Codepage EASTEUROPE_CHARSET
    * Codepage RUSSIAN_CHARSET
    * Codepage SYMBOL_CHARSET
    * Codepage SHIFTJIS_CHARSET
    * Codepage HANGEUL_CHARSET
    * Codepage GB2312_CHARSET
    * Codepage CHINESEBIG5_CHARSET
    * Codepage JOHAB_CHARSET
    * Codepage HEBREW_CHARSET
    * Codepage ARABIC_CHARSET
    * Codepage GREEK_CHARSET
    * Codepage TURKISH_CHARSET
    * Codepage VIETNAMESE_CHARSET
    * Codepage THAI_CHARSET
    * Codepage MAC_CHARSET
    * Codepage BALTIC_CHARSET
    * Codepage OEM_CHARSET
# GMAssetCompiler.IFFChunkSaver`1[T]
  ## Members
    * Void Invoke(T, System.IO.Stream, GMAssetCompiler.IFF)
    * System.IAsyncResult BeginInvoke(T, System.IO.Stream, GMAssetCompiler.IFF, System.AsyncCallback, System.Object)
    * Void EndInvoke(System.IAsyncResult)
    * Void GetObjectData(System.Runtime.Serialization.SerializationInfo, System.Runtime.Serialization.StreamingContext)
    * Boolean Equals(System.Object)
    * System.Delegate[] GetInvocationList()
    * Int32 GetHashCode()
    * System.Object DynamicInvoke(System.Object[])
    * System.Reflection.MethodInfo get_Method()
    * System.Object get_Target()
    * System.Object Clone()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor(System.Object, IntPtr)
    * System.Reflection.MethodInfo Method
    * System.Object Target
# GMAssetCompiler.IFFChunkType
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.IFFChunkType CPU
    * GMAssetCompiler.IFFChunkType GPU
    * GMAssetCompiler.IFFChunkType Audio
    * GMAssetCompiler.IFFChunkType Align
    * GMAssetCompiler.IFFChunkType Offset
# GMAssetCompiler.IIFFChunkHandler
  ## Members
    * GMAssetCompiler.IFFChunkType get_Type()
    * Int32 get_Align()
    * Int32 get_Offset()
    * System.String get_Name()
    * Void Save(System.IO.Stream, GMAssetCompiler.IFF)
    * GMAssetCompiler.IFFChunkType Type
    * Int32 Align
    * Int32 Offset
    * System.String Name
# GMAssetCompiler.IFFChunkHandler`1[T]
  ## Members
    * GMAssetCompiler.IFFChunkType get_Type()
    * Int32 get_Align()
    * Int32 get_Offset()
    * System.String get_Name()
    * Void Save(System.IO.Stream, GMAssetCompiler.IFF)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * GMAssetCompiler.IFFChunkType Type
    * Int32 Align
    * Int32 Offset
    * System.String Name
# GMAssetCompiler.IFFPatchEntry
  ## Members
    * Int64 get_Site()
    * System.Object get_Target()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(Int64, System.Object)
    * Int64 Site
    * System.Object Target
# GMAssetCompiler.IFFString
  ## Members
    * System.String get_String()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String)
    * System.String String
# GMAssetCompiler.IFF
  ## Members
    * System.Collections.Generic.List`1[GMAssetCompiler.IFFString] get_Strings()
    * System.Collections.Generic.Dictionary`2[System.String,System.Int32] get_StringCheck()
    * System.Collections.Generic.List`1[GMAssetCompiler.ExtraFile] get_ExternalFiles()
    * Void set_ExternalFiles(System.Collections.Generic.List`1[GMAssetCompiler.ExtraFile])
    * System.Collections.Generic.Dictionary`2[System.String,System.UInt32] get_ExternalFileAttributes()
    * Void set_ExternalFileAttributes(System.Collections.Generic.Dictionary`2[System.String,System.UInt32])
    * Int64 GetOffset(System.Object)
    * Void SetOffset(System.IO.Stream, System.Object, Int64)
    * GMAssetCompiler.IFFString AddString(System.String)
    * Void AddString(System.IO.Stream, System.String)
    * Void AddPatch(System.IO.Stream, System.Object)
    * Void RegisterChunk[T](System.String, GMAssetCompiler.IFFChunkSaver`1[T], T, GMAssetCompiler.IFFChunkType)
    * Void RegisterChunk[T](System.String, GMAssetCompiler.IFFChunkSaver`1[T], T, GMAssetCompiler.IFFChunkType, Int32)
    * Void RegisterChunk[T](System.String, GMAssetCompiler.IFFChunkSaver`1[T], T, GMAssetCompiler.IFFChunkType, Int32, Int32)
    * Void WriteChunks(System.IO.Stream)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.List`1[GMAssetCompiler.IFFString] Strings
    * System.Collections.Generic.Dictionary`2[System.String,System.Int32] StringCheck
    * System.Collections.Generic.List`1[GMAssetCompiler.ExtraFile] ExternalFiles
    * System.Collections.Generic.Dictionary`2[System.String,System.UInt32] ExternalFileAttributes
    * System.Collections.Generic.List`1[GMAssetCompiler.IIFFChunkHandler] m_chunks
    * System.Collections.Generic.Dictionary`2[System.Object,System.Collections.Generic.List`1[GMAssetCompiler.IFFPatchEntry]] m_patches
# GMAssetCompiler.Output.LLVM_Android
  ## Members
    * System.String get_NDKDir()
    * Void set_NDKDir(System.String)
    * System.String get_ARMToolChain()
    * Void set_ARMToolChain(System.String)
    * System.String get_MIPSToolChain()
    * Void set_MIPSToolChain(System.String)
    * System.String get_X86ToolChain()
    * Void set_X86ToolChain(System.String)
    * System.String get_PlatformDir()
    * Void set_PlatformDir(System.String)
    * System.String get_Name()
    * System.String get_Extension()
    * System.Collections.Generic.List`1[System.String] get_Archs()
    * Void Error(System.String, System.Object[])
    * Boolean ClangCompile(System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean CreateWADObj(System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * Boolean ClangLink(System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * System.String CreateExeName(System.String, System.String)
    * Boolean HasSeparateWAD()
    * Boolean HasWriteProject()
    * Boolean HasCompileAndLink()
    * Boolean WriteProject(System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[GMAssetCompiler.ExtraFile], GMAssetCompiler.GMAssets)
    * System.String GetWADExtension()
    * System.String GetArchDir(System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String NDKDir
    * System.String ARMToolChain
    * System.String MIPSToolChain
    * System.String X86ToolChain
    * System.String PlatformDir
    * System.String Name
    * System.String Extension
    * System.Collections.Generic.List`1[System.String] Archs
    * System.String ARMToolchainNumber
    * System.String ARMToolchainType
    * System.String MIPSToolchainNumber
    * System.String MIPSToolchainType
    * System.String X86ToolchainNumber
    * System.String X86ToolchainType
    * System.String PlatformNumber
# GMAssetCompiler.Output.XCodeProjID
  ## Members
    * UInt32 get_ID0()
    * Void set_ID0(UInt32)
    * UInt32 get_ID1()
    * Void set_ID1(UInt32)
    * UInt32 get_ID2()
    * Void set_ID2(UInt32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * UInt32 ID0
    * UInt32 ID1
    * UInt32 ID2
    * UInt32 OrigID0
    * UInt32 OrigID1
    * UInt32 OrigID2
# GMAssetCompiler.Output.XCodeProjEntry
  ## Members
    * System.String get_Name()
    * Void set_Name(System.String)
    * System.String get_DestName()
    * Void set_DestName(System.String)
    * GMAssetCompiler.Output.XCodeProjID get_BuildID()
    * Void set_BuildID(GMAssetCompiler.Output.XCodeProjID)
    * GMAssetCompiler.Output.XCodeProjID get_FileRefID()
    * Void set_FileRefID(GMAssetCompiler.Output.XCodeProjID)
    * GMAssetCompiler.Output.XCodeProjID get_GroupID()
    * Void set_GroupID(GMAssetCompiler.Output.XCodeProjID)
    * GMAssetCompiler.Output.XCodeProjID get_SourceID()
    * Void set_SourceID(GMAssetCompiler.Output.XCodeProjID)
    * System.String get_MacLoc()
    * Void set_MacLoc(System.String)
    * System.String get_CompilerFlags()
    * Void set_CompilerFlags(System.String)
    * Boolean get_WeakRef()
    * Void set_WeakRef(Boolean)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String, System.String, System.String)
    * Void .ctor(System.String)
    * System.String Name
    * System.String DestName
    * GMAssetCompiler.Output.XCodeProjID BuildID
    * GMAssetCompiler.Output.XCodeProjID FileRefID
    * GMAssetCompiler.Output.XCodeProjID GroupID
    * GMAssetCompiler.Output.XCodeProjID SourceID
    * System.String MacLoc
    * System.String CompilerFlags
    * Boolean WeakRef
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] embeddedFrameworkGroup
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] embeddedResourcesGroup
    * GMAssetCompiler.Output.XCodeCopyFileGroup embeddedResoruceFiles
# GMAssetCompiler.Output.XCodeCopyFileGroup
  ## Members
    * System.String get_DestPath()
    * Void set_DestPath(System.String)
    * GMAssetCompiler.Output.XCodeProjID get_GroupID()
    * Void set_GroupID(GMAssetCompiler.Output.XCodeProjID)
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] get_Files()
    * Void set_Files(System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry])
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String)
    * System.String DestPath
    * GMAssetCompiler.Output.XCodeProjID GroupID
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] Files
# GMAssetCompiler.Output.LLVM_iOS
  ## Members
    * System.String get_ToolChainDir()
    * Void set_ToolChainDir(System.String)
    * System.String get_FrameworkDir()
    * Void set_FrameworkDir(System.String)
    * System.String get_Name()
    * System.String get_Extension()
    * System.Collections.Generic.List`1[System.String] get_Archs()
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] get_SourceFiles()
    * Void set_SourceFiles(System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry])
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] get_BundledFiles()
    * Void set_BundledFiles(System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry])
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] get_ExtraFiles()
    * Void set_ExtraFiles(System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry])
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] get_FrameworkFiles()
    * Void set_FrameworkFiles(System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry])
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] get_LocalFrameworkFiles()
    * Void set_LocalFrameworkFiles(System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry])
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] get_EmbeddedFrameworkFiles()
    * Void set_EmbeddedFrameworkFiles(System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry])
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] get_LocalExtraFiles()
    * Void set_LocalExtraFiles(System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry])
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeCopyFileGroup] get_FileGroups()
    * Void set_FileGroups(System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeCopyFileGroup])
    * Void Error(System.String, System.Object[])
    * Boolean ClangCompile(System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean CreateWADObj(System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * System.String CreatePBXGroups()
    * System.String CreateBuildSection()
    * System.String GetType(System.String)
    * System.String CreateFileRefSection()
    * System.String CreateGroupSection()
    * System.String CreateSourceSection()
    * System.String CreateFrameworkGroup()
    * System.String AddLDFlags(GMAssetCompiler.GMAssets)
    * System.String CreateExtraBuildSettings(GMAssetCompiler.GMAssets, System.String)
    * System.String CreateResourcesBuildPhase()
    * System.String CreateFrameworkBuildSection()
    * System.String CreateExtraFilesSection(System.String ByRef)
    * System.String CreateSupportingFilesGroup()
    * Boolean ClangLink(System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * Void WriteExtensionToIniFile(GMAssetCompiler.GMAssets)
    * Void AddDirFilesToProj(System.String, System.Uri, System.String)
    * Boolean WriteProject(System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[GMAssetCompiler.ExtraFile], GMAssetCompiler.GMAssets)
    * System.String CreateExeName(System.String, System.String)
    * Boolean HasSeparateWAD()
    * Boolean HasWriteProject()
    * Boolean HasCompileAndLink()
    * System.String GetWADExtension()
    * System.String GetArchDir(System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String ToolChainDir
    * System.String FrameworkDir
    * System.String Name
    * System.String Extension
    * System.Collections.Generic.List`1[System.String] Archs
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] SourceFiles
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] BundledFiles
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] ExtraFiles
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] FrameworkFiles
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] LocalFrameworkFiles
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] EmbeddedFrameworkFiles
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] LocalExtraFiles
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeCopyFileGroup] FileGroups
# GMAssetCompiler.Output.LLVM_Linux
  ## Members
    * System.String get_SDKDir()
    * Void set_SDKDir(System.String)
    * System.String get_Name()
    * System.String get_Extension()
    * System.Collections.Generic.List`1[System.String] get_Archs()
    * Void Error(System.String, System.Object[])
    * Boolean ClangCompile(System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean ClangLink(System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * Boolean CreateWADObj(System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * System.String CreateExeName(System.String, System.String)
    * Boolean HasSeparateWAD()
    * Boolean HasWriteProject()
    * Boolean HasCompileAndLink()
    * Boolean WriteProject(System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[GMAssetCompiler.ExtraFile], GMAssetCompiler.GMAssets)
    * System.String GetWADExtension()
    * System.String GetArchDir(System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String SDKDir
    * System.String Name
    * System.String Extension
    * System.Collections.Generic.List`1[System.String] Archs
# GMAssetCompiler.Output.LLVM_Mac
  ## Members
    * System.String get_ToolChainDir()
    * Void set_ToolChainDir(System.String)
    * System.String get_FrameworkDir()
    * Void set_FrameworkDir(System.String)
    * System.String get_Name()
    * System.String get_Extension()
    * System.Collections.Generic.List`1[System.String] get_Archs()
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] get_SourceFiles()
    * Void set_SourceFiles(System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry])
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] get_BundledFiles()
    * Void set_BundledFiles(System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry])
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] get_ExtraFiles()
    * Void set_ExtraFiles(System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry])
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] get_FrameworkFiles()
    * Void set_FrameworkFiles(System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry])
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] get_LocalFrameworkFiles()
    * Void set_LocalFrameworkFiles(System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry])
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] get_LocalExtraFiles()
    * Void set_LocalExtraFiles(System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry])
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeCopyFileGroup] get_FileGroups()
    * Void set_FileGroups(System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeCopyFileGroup])
    * Void Error(System.String, System.Object[])
    * Boolean ClangCompile(System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean CreateWADObj(System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * Boolean IsBuildingForAppStore()
    * Boolean ShouldRemoveGamepads()
    * System.String CreateBuildSection()
    * System.String CreateFileRefSection()
    * System.String CreateGroupSection()
    * System.String CreateSourceSection()
    * System.String CreateFrameworkGroup()
    * System.String AddLDFlags(GMAssetCompiler.GMAssets)
    * System.String CreateExtraBuildSettings(GMAssetCompiler.GMAssets, System.String)
    * System.String CreateResourcesBuildPhase()
    * System.String CreateFrameworkBuildSection()
    * System.String CreateExtraFilesSection(System.String ByRef)
    * System.String CreateSupportingFilesGroup()
    * Boolean ClangLink(System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * Void WriteExtensionToIniFile(GMAssetCompiler.GMAssets)
    * Void AddDirFilesToProj(System.String, System.Uri)
    * Boolean WriteProject(System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[GMAssetCompiler.ExtraFile], GMAssetCompiler.GMAssets)
    * System.String CreateExeName(System.String, System.String)
    * Boolean HasSeparateWAD()
    * Boolean HasWriteProject()
    * Boolean HasCompileAndLink()
    * System.String GetWADExtension()
    * System.String GetArchDir(System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String ToolChainDir
    * System.String FrameworkDir
    * System.String Name
    * System.String Extension
    * System.Collections.Generic.List`1[System.String] Archs
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] SourceFiles
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] BundledFiles
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] ExtraFiles
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] FrameworkFiles
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] LocalFrameworkFiles
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeProjEntry] LocalExtraFiles
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.XCodeCopyFileGroup] FileGroups
# GMAssetCompiler.Output.LLVM_PS3
  ## Members
    * System.String get_SDKDir()
    * Void set_SDKDir(System.String)
    * System.String get_Name()
    * System.String get_Extension()
    * System.Collections.Generic.List`1[System.String] get_Archs()
    * Void Error(System.String, System.Object[])
    * Boolean ClangCompile(System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean CreateWADObj(System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * Boolean ClangLink(System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * System.String CreateExeName(System.String, System.String)
    * Boolean HasSeparateWAD()
    * Boolean HasWriteProject()
    * Boolean HasCompileAndLink()
    * Boolean WriteProject(System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[GMAssetCompiler.ExtraFile], GMAssetCompiler.GMAssets)
    * System.String GetWADExtension()
    * System.String GetArchDir(System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String SDKDir
    * System.String Name
    * System.String Extension
    * System.Collections.Generic.List`1[System.String] Archs
# GMAssetCompiler.Output.LLVM_PS4
  ## Members
    * System.String get_SDKDir()
    * Void set_SDKDir(System.String)
    * System.String get_Name()
    * System.String get_Extension()
    * System.Collections.Generic.List`1[System.String] get_Archs()
    * Void Error(System.String, System.Object[])
    * Boolean ClangCompile(System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean CreateWADObj(System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * Boolean ClangLink(System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * System.String CreateExeName(System.String, System.String)
    * Boolean HasSeparateWAD()
    * Boolean HasWriteProject()
    * Boolean HasCompileAndLink()
    * Boolean WriteProject(System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[GMAssetCompiler.ExtraFile], GMAssetCompiler.GMAssets)
    * System.String GetWADExtension()
    * System.String GetArchDir(System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String SDKDir
    * System.String Name
    * System.String Extension
    * System.Collections.Generic.List`1[System.String] Archs
# GMAssetCompiler.Output.LLVM_PSVita
  ## Members
    * System.String get_SDKDir()
    * Void set_SDKDir(System.String)
    * System.String get_Name()
    * System.String get_Extension()
    * System.Collections.Generic.List`1[System.String] get_Archs()
    * Void Error(System.String, System.Object[])
    * Boolean ClangCompile(System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean CreateWADObj(System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * Boolean ClangLink(System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * System.String CreateExeName(System.String, System.String)
    * Boolean HasSeparateWAD()
    * Boolean HasWriteProject()
    * Boolean HasCompileAndLink()
    * Boolean WriteProject(System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[GMAssetCompiler.ExtraFile], GMAssetCompiler.GMAssets)
    * System.String GetWADExtension()
    * System.String GetArchDir(System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String SDKDir
    * System.String Name
    * System.String Extension
    * System.Collections.Generic.List`1[System.String] Archs
# GMAssetCompiler.Output.LLVM_Tizen
  ## Members
    * System.String get_TizenSDKDir()
    * Void set_TizenSDKDir(System.String)
    * System.String get_Name()
    * System.String get_Extension()
    * System.Collections.Generic.List`1[System.String] get_Archs()
    * Boolean ClangCompile(System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean CreateWADObj(System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * Boolean ClangLink(System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * System.String CreateExeName(System.String, System.String)
    * Boolean HasSeparateWAD()
    * Boolean HasWriteProject()
    * Boolean HasCompileAndLink()
    * Boolean WriteProject(System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[GMAssetCompiler.ExtraFile], GMAssetCompiler.GMAssets)
    * System.String GetWADExtension()
    * System.String GetArchDir(System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String TizenSDKDir
    * System.String Name
    * System.String Extension
    * System.Collections.Generic.List`1[System.String] Archs
# GMAssetCompiler.Output.LLVM_Windows
  ## Members
    * System.String get_VisualStudioDir()
    * Void set_VisualStudioDir(System.String)
    * System.String get_DirectXDir()
    * Void set_DirectXDir(System.String)
    * System.String get_WindowsSDKDir()
    * Void set_WindowsSDKDir(System.String)
    * System.String get_LinkEXE()
    * Void set_LinkEXE(System.String)
    * System.String get_MtEXE()
    * Void set_MtEXE(System.String)
    * System.String get_RcEXE()
    * Void set_RcEXE(System.String)
    * System.String get_WindowsSDKLibDir()
    * Void set_WindowsSDKLibDir(System.String)
    * System.String get_Name()
    * System.String get_Extension()
    * System.Collections.Generic.List`1[System.String] get_Archs()
    * Boolean ClangCompile(System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean CreateWADObj(System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * Boolean ClangLink(System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * System.String CreateExeName(System.String, System.String)
    * Boolean HasSeparateWAD()
    * Boolean HasWriteProject()
    * Boolean HasCompileAndLink()
    * Boolean WriteProject(System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[GMAssetCompiler.ExtraFile], GMAssetCompiler.GMAssets)
    * System.String GetWADExtension()
    * System.String GetArchDir(System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String VisualStudioDir
    * System.String DirectXDir
    * System.String WindowsSDKDir
    * System.String LinkEXE
    * System.String MtEXE
    * System.String RcEXE
    * System.String WindowsSDKLibDir
    * System.String Name
    * System.String Extension
    * System.Collections.Generic.List`1[System.String] Archs
# GMAssetCompiler.Output.LLVM_Windows8
  ## Members
    * System.String get_SDKDir()
    * Void set_SDKDir(System.String)
    * System.String get_Name()
    * System.String get_Extension()
    * System.Collections.Generic.List`1[System.String] get_Archs()
    * Void Error(System.String, System.Object[])
    * Boolean ClangCompile(System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean CreateWADObj(System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * Boolean ClangLink(System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * System.String CreateExeName(System.String, System.String)
    * Boolean HasSeparateWAD()
    * Boolean HasWriteProject()
    * Boolean HasCompileAndLink()
    * Boolean WriteProject(System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[GMAssetCompiler.ExtraFile], GMAssetCompiler.GMAssets)
    * System.String GetWADExtension()
    * System.String GetArchDir(System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String SDKDir
    * System.String Name
    * System.String Extension
    * System.Collections.Generic.List`1[System.String] Archs
# GMAssetCompiler.Output.LLVM_WindowsPhone
  ## Members
    * System.String get_SDKDir()
    * Void set_SDKDir(System.String)
    * System.String get_Name()
    * System.String get_Extension()
    * System.Collections.Generic.List`1[System.String] get_Archs()
    * Void Error(System.String, System.Object[])
    * Boolean ClangCompile(System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean CreateWADObj(System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * Boolean ClangLink(System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * System.String CreateExeName(System.String, System.String)
    * Boolean HasSeparateWAD()
    * Boolean HasWriteProject()
    * Boolean HasCompileAndLink()
    * Boolean WriteProject(System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[GMAssetCompiler.ExtraFile], GMAssetCompiler.GMAssets)
    * System.String GetWADExtension()
    * System.String GetArchDir(System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String SDKDir
    * System.String Name
    * System.String Extension
    * System.Collections.Generic.List`1[System.String] Archs
# GMAssetCompiler.Output.LLVM_XBoxOne
  ## Members
    * System.String get_SDKDir()
    * Void set_SDKDir(System.String)
    * System.String get_Name()
    * System.String get_Extension()
    * System.Collections.Generic.List`1[System.String] get_Archs()
    * Void Error(System.String, System.Object[])
    * Boolean ClangCompile(System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean CreateWADObj(System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * Boolean ClangLink(System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * System.String CreateExeName(System.String, System.String)
    * Boolean HasSeparateWAD()
    * Boolean HasWriteProject()
    * Boolean HasCompileAndLink()
    * Boolean WriteProject(System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[GMAssetCompiler.ExtraFile], GMAssetCompiler.GMAssets)
    * System.String GetWADExtension()
    * System.String GetArchDir(System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String SDKDir
    * System.String Name
    * System.String Extension
    * System.Collections.Generic.List`1[System.String] Archs
# GMAssetCompiler.WADSaver`1[TCode]
  ## Members
    * Void ParseGMLFile(GMAssetCompiler.GMExtension, GMAssetCompiler.GMExtensionInclude, System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.GMExtensionFunction])
    * Boolean CompileAllCode(GMAssetCompiler.GMAssets)
    * Void WriteDebugInfo(System.Collections.Generic.IList`1[TCode], System.IO.Stream, GMAssetCompiler.IFF)
    * Void WriteDebugInstNames(System.Collections.Generic.IList`1[System.String], System.IO.Stream, GMAssetCompiler.IFF)
    * Void WriteDebugScripts(System.Collections.Generic.IList`1[TCode], System.IO.Stream, GMAssetCompiler.IFF)
    * Void WriteDebugLocalVariables(System.Collections.Generic.IList`1[TCode], System.IO.Stream, GMAssetCompiler.IFF)
    * Void WriteFUNC(System.Collections.Generic.IList`1[TCode], System.IO.Stream, GMAssetCompiler.IFF)
    * Void WriteVARI(System.Collections.Generic.IList`1[TCode], System.IO.Stream, GMAssetCompiler.IFF)
    * Void WriteCode(System.Collections.Generic.IList`1[TCode], System.IO.Stream, GMAssetCompiler.IFF)
    * Void SaveDebugInfo(GMAssetCompiler.GMAssets, System.IO.Stream)
    * Void SaveAudioGroups(GMAssetCompiler.GMAssets, System.Collections.Generic.List`1[GMAssetCompiler.ExtraFile])
    * Void Save(GMAssetCompiler.GMAssets, System.IO.Stream, System.Collections.Generic.List`1[GMAssetCompiler.ExtraFile], System.Collections.Generic.Dictionary`2[System.String,System.UInt32])
    * Void WriteDataList[T](System.Collections.Generic.IList`1[T], System.IO.Stream, GMAssetCompiler.IFF, WriteDelegate`1)
    * Int32 GetCompiledCodeIndex(Int32)
    * Void Get1stRoomSize(GMAssetCompiler.GMAssets, Int32 ByRef, Int32 ByRef)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * GMAssetCompiler.TexturePage ms_tpageSprites
    * System.Collections.Generic.List`1[GMAssetCompiler.Wave] ms_Waves
    * System.Collections.Generic.List`1[GMAssetCompiler.Wave][] ms_GroupWaves
    * System.Collections.Generic.List`1[TCode] ms_code
    * System.Collections.Generic.Dictionary`2[System.String,TCode] ms_scripts
    * System.Collections.Generic.List`1[System.String] ms_CCInstNames
    * GMAssetCompiler.WADSaver`1+WriteDelegateKVP`1[TCode,T]
    * GMAssetCompiler.WADSaver`1+WriteDelegate`1[TCode,T]
# GMAssetCompiler.WADSaver`1+_EtxPopulationSample[TCode]
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * _EtxPopulationSample ProviderDefault
    * _EtxPopulationSample SystemDefault
    * _EtxPopulationSample Undefined
# GMAssetCompiler.WADSaver`1+_EtxProviderLatency[TCode]
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * _EtxProviderLatency Undefined
    * _EtxProviderLatency Normal
    * _EtxProviderLatency RealTime
    * _EtxProviderLatency MaxValue
# GMAssetCompiler.WADSaver`1+_EtxEventLatency[TCode]
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * _EtxEventLatency Undefined
    * _EtxEventLatency Normal
    * _EtxEventLatency RealTime
    * _EtxEventLatency ProviderDefault
    * _EtxEventLatency MaxValue
# GMAssetCompiler.WADSaver`1+_EtxProviderPriority[TCode]
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * _EtxProviderPriority Undefined
    * _EtxProviderPriority Normal
    * _EtxProviderPriority Critical
    * _EtxProviderPriority MaxValue
# GMAssetCompiler.WADSaver`1+_EtxEventPriority[TCode]
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * _EtxEventPriority Undefined
    * _EtxEventPriority Normal
    * _EtxEventPriority Critical
    * _EtxEventPriority ProviderDefault
    * _EtxEventPriority MaxValue
# GMAssetCompiler.WADSaver`1+_EtxProviderEnabledState[TCode]
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * _EtxProviderEnabledState Undefined
    * _EtxProviderEnabledState ForceOff
    * _EtxProviderEnabledState OffByDefault
    * _EtxProviderEnabledState OnByDefault
    * _EtxProviderEnabledState ForceOn
    * _EtxProviderEnabledState MaxValue
# GMAssetCompiler.WADSaver`1+_EtxEventEnabledState[TCode]
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * _EtxEventEnabledState Undefined
    * _EtxEventEnabledState Off
    * _EtxEventEnabledState ProviderDefault
    * _EtxEventEnabledState On
    * _EtxEventEnabledState MaxValue
# GMAssetCompiler.WADSaver`1+_EtxFieldType[TCode]
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * _EtxFieldType UnicodeString
    * _EtxFieldType Int8
    * _EtxFieldType UInt8
    * _EtxFieldType Int16
    * _EtxFieldType UInt16
    * _EtxFieldType Int32
    * _EtxFieldType UInt32
    * _EtxFieldType Int64
    * _EtxFieldType UInt64
    * _EtxFieldType Float
    * _EtxFieldType Double
    * _EtxFieldType Boolean
    * _EtxFieldType Binary
    * _EtxFieldType GUID
    * _EtxFieldType Pointer
    * _EtxFieldType FILETIME
    * _EtxFieldType SYSTEMTIME
    * _EtxFieldType CountedUnicodeString
    * _EtxFieldType IPv4
    * _EtxFieldType IPv6
    * _EtxFieldType MaxValue
# GMAssetCompiler.WADSaver`1+WriteDelegateKVP`1[TCode,T]
  ## Members
    * Void Invoke(System.Collections.Generic.KeyValuePair`2[System.String,T], System.IO.Stream, GMAssetCompiler.IFF, Int64)
    * System.IAsyncResult BeginInvoke(System.Collections.Generic.KeyValuePair`2[System.String,T], System.IO.Stream, GMAssetCompiler.IFF, Int64, System.AsyncCallback, System.Object)
    * Void EndInvoke(System.IAsyncResult)
    * Void GetObjectData(System.Runtime.Serialization.SerializationInfo, System.Runtime.Serialization.StreamingContext)
    * Boolean Equals(System.Object)
    * System.Delegate[] GetInvocationList()
    * Int32 GetHashCode()
    * System.Object DynamicInvoke(System.Object[])
    * System.Reflection.MethodInfo get_Method()
    * System.Object get_Target()
    * System.Object Clone()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor(System.Object, IntPtr)
    * System.Reflection.MethodInfo Method
    * System.Object Target
# GMAssetCompiler.WADSaver`1+WriteDelegate`1[TCode,T]
  ## Members
    * Void Invoke(T, System.IO.Stream, GMAssetCompiler.IFF, Int64)
    * System.IAsyncResult BeginInvoke(T, System.IO.Stream, GMAssetCompiler.IFF, Int64, System.AsyncCallback, System.Object)
    * Void EndInvoke(System.IAsyncResult)
    * Void GetObjectData(System.Runtime.Serialization.SerializationInfo, System.Runtime.Serialization.StreamingContext)
    * Boolean Equals(System.Object)
    * System.Delegate[] GetInvocationList()
    * Int32 GetHashCode()
    * System.Object DynamicInvoke(System.Object[])
    * System.Reflection.MethodInfo get_Method()
    * System.Object get_Target()
    * System.Object Clone()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor(System.Object, IntPtr)
    * System.Reflection.MethodInfo Method
    * System.Object Target
# GMAssetCompiler.LLVMSaver
  ## Members
    * System.String get_CPPDir()
    * Void set_CPPDir(System.String)
    * Void Save(GMAssetCompiler.GMAssets, System.String)
    * Void ParseGMLFile(GMAssetCompiler.GMExtension, GMAssetCompiler.GMExtensionInclude, System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.GMExtensionFunction])
    * Boolean CompileAllCode(GMAssetCompiler.GMAssets)
    * Void WriteDebugInfo(System.Collections.Generic.IList`1[GMAssetCompiler.GML2CPP], System.IO.Stream, GMAssetCompiler.IFF)
    * Void WriteDebugInstNames(System.Collections.Generic.IList`1[System.String], System.IO.Stream, GMAssetCompiler.IFF)
    * Void WriteDebugScripts(System.Collections.Generic.IList`1[GMAssetCompiler.GML2CPP], System.IO.Stream, GMAssetCompiler.IFF)
    * Void WriteDebugLocalVariables(System.Collections.Generic.IList`1[GMAssetCompiler.GML2CPP], System.IO.Stream, GMAssetCompiler.IFF)
    * Void WriteFUNC(System.Collections.Generic.IList`1[GMAssetCompiler.GML2CPP], System.IO.Stream, GMAssetCompiler.IFF)
    * Void WriteVARI(System.Collections.Generic.IList`1[GMAssetCompiler.GML2CPP], System.IO.Stream, GMAssetCompiler.IFF)
    * Void WriteCode(System.Collections.Generic.IList`1[GMAssetCompiler.GML2CPP], System.IO.Stream, GMAssetCompiler.IFF)
    * Void SaveDebugInfo(GMAssetCompiler.GMAssets, System.IO.Stream)
    * Void SaveAudioGroups(GMAssetCompiler.GMAssets, System.Collections.Generic.List`1[GMAssetCompiler.ExtraFile])
    * Void Save(GMAssetCompiler.GMAssets, System.IO.Stream, System.Collections.Generic.List`1[GMAssetCompiler.ExtraFile], System.Collections.Generic.Dictionary`2[System.String,System.UInt32])
    * Void WriteDataList[T](System.Collections.Generic.IList`1[T], System.IO.Stream, GMAssetCompiler.IFF, WriteDelegate`1)
    * Int32 GetCompiledCodeIndex(Int32)
    * Void Get1stRoomSize(GMAssetCompiler.GMAssets, Int32 ByRef, Int32 ByRef)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String CPPDir
# GMAssetCompiler.GMLCPPFunction
  ## Members
    * System.String get_GMLName()
    * Void set_GMLName(System.String)
    * GMAssetCompiler.eVM_Type get_RetType()
    * Void set_RetType(GMAssetCompiler.eVM_Type)
    * System.Collections.Generic.List`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.eVM_Type]] get_Args()
    * Void set_Args(System.Collections.Generic.List`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.eVM_Type]])
    * System.String get_CPPName()
    * Void set_CPPName(System.String)
    * Boolean get_VarArgs()
    * Void set_VarArgs(Boolean)
    * System.String GetPrototype()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String, System.String, System.String)
    * Void .ctor(System.String, System.String, GMAssetCompiler.eVM_Type)
    * System.String GMLName
    * GMAssetCompiler.eVM_Type RetType
    * System.Collections.Generic.List`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.eVM_Type]] Args
    * System.String CPPName
    * Boolean VarArgs
# GMAssetCompiler.TypeDecorator
  ## Members
    * System.Collections.Generic.Stack`1[GMAssetCompiler.eVM_Type] get_TypeStack()
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.GMLCPPFunction] get_GMLFunctions()
    * Void DoIt(GMAssetCompiler.GMLToken)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.Stack`1[GMAssetCompiler.eVM_Type] TypeStack
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.GMLCPPFunction] GMLFunctions
# GMAssetCompiler.TexturesBlock
  ## Members
    * Int32 get_Scaled()
    * Void set_Scaled(Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(Int32)
    * Int32 Scaled
# GMAssetCompiler.UTF8Marshaler
  ## Members
    * IntPtr MarshalManagedToNative(System.Object)
    * System.Object MarshalNativeToManaged(IntPtr)
    * Void CleanUpNativeData(IntPtr)
    * Void CleanUpManagedData(System.Object)
    * Int32 GetNativeDataSize()
    * System.Runtime.InteropServices.ICustomMarshaler GetInstance(System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
# GMAssetCompiler.YYJSPatchEntry
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 index
    * Int32 type
    * Int64 offset
# GMAssetCompiler.YYJSScriptArgEntry
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 index
# GMAssetCompiler.YYJSLocalEntry
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 indexDecorated
    * Int32 indexUndecorated
# GMAssetCompiler.YYJSScriptEntry
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 indexDecorated
    * Int32 indexUndecorated
    * Int64 offset
    * IntPtr pParentScript
    * Int32 numArgs
    * IntPtr pArgs
    * Int32 numLocals
    * IntPtr pLocals
    * Int32 numInstanceVars
    * IntPtr pInstanceVars
# GMAssetCompiler.YYJSResult
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 result
    * IntPtr pParser
    * IntPtr pName
    * IntPtr pBuffer
    * Int64 bufferSize
    * IntPtr pDebugBuffer
    * Int64 bufferDebugSize
    * Int32 numErrors
    * IntPtr ppErrors
    * Int32 numStrings
    * IntPtr ppStrings
    * Int32 numVarPatches
    * IntPtr ppVarPatches
    * Int32 numFuncPatches
    * IntPtr ppFuncPatches
    * Int32 numStringPatches
    * IntPtr ppStringPatches
    * Int32 numScripts
    * IntPtr ppScriptEntries
# GMAssetCompiler.eVarPatchType
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.eVarPatchType eVPT_Global
    * GMAssetCompiler.eVarPatchType eVPT_BuiltIn
    * GMAssetCompiler.eVarPatchType eVPT_Local
    * GMAssetCompiler.eVarPatchType eVPT_Instance
    * GMAssetCompiler.eVarPatchType eVPT_RefOnStack
# GMAssetCompiler.YoYoJS
  ## Members
    * Void Init()
    * Void Quit()
    * IntPtr Parse(System.String, System.String, System.String)
    * IntPtr Compile(IntPtr, Boolean)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
# GMAssetCompiler.Win32MapApis
  ## Members
    * IntPtr CreateFile(System.String, Int32, Int32, IntPtr, Int32, Int32, IntPtr)
    * IntPtr CreateFileMapping(IntPtr, IntPtr, Int32, Int32, Int32, System.String)
    * Boolean FlushViewOfFile(IntPtr, Int32)
    * IntPtr MapViewOfFile(IntPtr, Int32, Int32, Int32, IntPtr)
    * IntPtr OpenFileMapping(Int32, Boolean, System.String)
    * Boolean UnmapViewOfFile(IntPtr)
    * Boolean CloseHandle(IntPtr)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 FileMapCopy
    * Int32 FileMapWrite
    * Int32 FileMapRead
    * Int32 FileMapAllAccess
# GMAssetCompiler.GMLFunctionInExtensionUsed
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMExtension, GMAssetCompiler.GMExtensionInclude, GMAssetCompiler.GMExtensionFunction)
    * GMAssetCompiler.GMExtension extension
    * GMAssetCompiler.GMExtensionInclude include
    * GMAssetCompiler.GMExtensionFunction function
# GMAssetCompiler.Program
  ## Members
    * System.String get_ConfigFileName()
    * Void set_ConfigFileName(System.String)
    * Int32 get_MajorVersion()
    * Void set_MajorVersion(Int32)
    * Int32 get_MinorVersion()
    * Void set_MinorVersion(Int32)
    * Int32 get_ReleaseVersion()
    * Void set_ReleaseVersion(Int32)
    * Int32 get_BuildVersion()
    * Void set_BuildVersion(Int32)
    * System.String get_GameName()
    * Void set_GameName(System.String)
    * Boolean get_DebugOutput()
    * Void set_DebugOutput(Boolean)
    * Boolean get_BuildMetroProj()
    * Void set_BuildMetroProj(Boolean)
    * System.String get_MetroProjLocation()
    * Void set_MetroProjLocation(System.String)
    * Boolean get_SteamProject()
    * Void set_SteamProject(Boolean)
    * Int32 get_SteamAppId()
    * Void set_SteamAppId(Int32)
    * System.String get_SteamLibrary()
    * Void set_SteamLibrary(System.String)
    * Int32 get_StudioEdition()
    * Void set_StudioEdition(Int32)
    * Boolean get_Quiet()
    * Void set_Quiet(Boolean)
    * Boolean get_GenerateSWFImages()
    * Void set_GenerateSWFImages(Boolean)
    * System.String get_SWFFilename()
    * Void set_SWFFilename(System.String)
    * Single get_SWFPrecision()
    * Void set_SWFPrecision(Single)
    * System.String get_SpineFilename()
    * Void set_SpineFilename(System.String)
    * Boolean get_GenerateSpineImage()
    * Void set_GenerateSpineImage(Boolean)
    * Boolean get_GetSpineRootX()
    * Void set_GetSpineRootX(Boolean)
    * Boolean get_GetSpineRootY()
    * Void set_GetSpineRootY(Boolean)
    * System.String get_PS4SDKDir()
    * Void set_PS4SDKDir(System.String)
    * System.String get_PSVitaSDKDir()
    * Void set_PSVitaSDKDir(System.String)
    * System.String get_PS3SDKDir()
    * Void set_PS3SDKDir(System.String)
    * Int32 get_DebuggerPort()
    * Void set_DebuggerPort(Int32)
    * System.String get_HostIP()
    * Void set_HostIP(System.String)
    * Int32 get_HostPort()
    * Void set_HostPort(Int32)
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.Program+TextureGroup] get_TextureGroups()
    * Void set_TextureGroups(System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.Program+TextureGroup])
    * TextureGroup FindTextureGroup(System.String)
    * System.String CleanPath(System.String)
    * System.String TextureTypeExtension(GMAssetCompiler.eTexType)
    * System.IO.TextWriter get_Out()
    * Void set_Out(System.IO.TextWriter)
    * System.IO.TextWriter get_Error()
    * Void set_Error(System.IO.TextWriter)
    * Void SetMachineType(System.String)
    * Void DoPreObfuscateLib(System.String, System.String)
    * Void CheckSecurity()
    * Void Warning(System.String, System.Collections.Generic.KeyValuePair`2[GMAssetCompiler.GMLCode,GMAssetCompiler.GMLToken])
    * Void MakeTextureGroups(GMAssetCompiler.GMAssets)
    * Double GetUnixEpoch(System.DateTime)
    * Int32 GetLineNumber(System.String, Int32, System.String ByRef)
    * Void ErrorWrite(System.String, System.Object[])
    * System.String RemoveSpaces(System.String)
    * System.String MakeValidName(System.String)
    * System.String MakeValidNameNoSB(System.String)
    * System.String SubstituteEnv(System.Collections.Generic.Dictionary`2[System.String,System.String], System.String)
    * Byte[] MD5File(System.String)
    * Byte[] MD5Array(Byte[])
    * Byte[] MD5StringList(System.String[])
    * Boolean CompareMD5(Byte[], Byte[])
    * Void CopyAndSubstituteEnv(System.Collections.Generic.Dictionary`2[System.String,System.String], System.String, System.String)
    * Void CopyDirAndSubstituteEnv(System.Collections.Generic.Dictionary`2[System.String,System.String], System.String, System.String)
    * Boolean IsCacheFileValid(System.String, System.String[])
    * System.String GetTempFileName()
    * System.Collections.Generic.List`1[R] ParallelExec[R,T](System.Collections.Generic.IList`1[T], Del_ParallelExec`2)
    * Byte[] MD5StringToByteArray(System.String)
    * System.String MD5ByteArrayToString(Byte[])
    * System.String PathCombine(System.String, System.String[])
    * Boolean get_StudioData()
    * Void set_StudioData(Boolean)
    * Int32 get_MakerValue()
    * Void set_MakerValue(Int32)
    * Int64 get_TargetMask()
    * Void set_TargetMask(Int64)
    * System.Collections.Generic.List`1[GMAssetCompiler.GMLFunctionInExtensionUsed] get_ExtensionFunctionsUsed()
    * Void set_ExtensionFunctionsUsed(System.Collections.Generic.List`1[GMAssetCompiler.GMLFunctionInExtensionUsed])
    * GMAssetCompiler.IMachineType get_MachineType()
    * Void set_MachineType(GMAssetCompiler.IMachineType)
    * System.String get_OutputDir()
    * Void set_OutputDir(System.String)
    * Boolean get_WriteTextures()
    * Void set_WriteTextures(Boolean)
    * Boolean get_WriteWaves()
    * Void set_WriteWaves(Boolean)
    * Boolean get_CompileOnly()
    * Void set_CompileOnly(Boolean)
    * Boolean get_SplashOmit()
    * Void set_SplashOmit(Boolean)
    * Boolean get_SeparateOpaqueAndAlpha()
    * Void set_SeparateOpaqueAndAlpha(Boolean)
    * Boolean get_DisplaySortedTextures()
    * Void set_DisplaySortedTextures(Boolean)
    * Int32 get_TexturePageWidth()
    * Void set_TexturePageWidth(Int32)
    * Int32 get_TexturePageHeight()
    * Void set_TexturePageHeight(Int32)
    * Int32 get_TextureScale()
    * Void set_TextureScale(Int32)
    * Boolean get_Verbose()
    * Void set_Verbose(Boolean)
    * Boolean get_CompileVerbose()
    * Void set_CompileVerbose(Boolean)
    * Boolean get_RemoveDND()
    * Void set_RemoveDND(Boolean)
    * Boolean get_CenterHTML5Game()
    * Void set_CenterHTML5Game(Boolean)
    * Boolean get_TargetRunner()
    * Void set_TargetRunner(Boolean)
    * Boolean get_NoCache()
    * Void set_NoCache(Boolean)
    * Boolean get_NoIndexHTML()
    * Void set_NoIndexHTML(Boolean)
    * System.String get_HTMLRunner()
    * Void set_HTMLRunner(System.String)
    * System.String get_ShaderPreamble()
    * Void set_ShaderPreamble(System.String)
    * Boolean get_DoObfuscate()
    * Void set_DoObfuscate(Boolean)
    * Boolean get_ObfuscateObfuscate()
    * Void set_ObfuscateObfuscate(Boolean)
    * Boolean get_ObfuscatePrettyPrint()
    * Void set_ObfuscatePrettyPrint(Boolean)
    * Boolean get_ObfuscateRemoveUnused()
    * Void set_ObfuscateRemoveUnused(Boolean)
    * Boolean get_ObfuscateEncodeStrings()
    * Void set_ObfuscateEncodeStrings(Boolean)
    * System.String get_LoadingBarName()
    * Void set_LoadingBarName(System.String)
    * Boolean get_CustomLoadingScreen()
    * Void set_CustomLoadingScreen(Boolean)
    * Int32 get_ExitCode()
    * Void set_ExitCode(Int32)
    * Boolean get_InhibitErrorOutput()
    * Void set_InhibitErrorOutput(Boolean)
    * System.String get_PreObfuscateLib()
    * Void set_PreObfuscateLib(System.String)
    * GMAssetCompiler.GMAssets get_Assets()
    * Void set_Assets(GMAssetCompiler.GMAssets)
    * Boolean get_Studio()
    * Void set_Studio(Boolean)
    * System.String get_OptionsIniFileName()
    * Void set_OptionsIniFileName(System.String)
    * Boolean get_CompileToVM()
    * Void set_CompileToVM(Boolean)
    * System.String get_WorkingDirectory()
    * Void set_WorkingDirectory(System.String)
    * Int32 get_Fellowship()
    * Void set_Fellowship(Int32)
    * Int32 get_Cabal()
    * Void set_Cabal(Int32)
    * GMAssetCompiler.CheckLicense get_License()
    * Void set_License(GMAssetCompiler.CheckLicense)
    * System.String get_HTML5GameFolder()
    * Void set_HTML5GameFolder(System.String)
    * System.Globalization.CultureInfo get_InvariantCulture()
    * Void set_InvariantCulture(System.Globalization.CultureInfo)
    * System.String get_FunctionsUsedOutputFile()
    * Void set_FunctionsUsedOutputFile(System.String)
    * System.String get_EducationMode()
    * Void set_EducationMode(System.String)
    * Boolean get_LowerCaseExternalFilenames()
    * Void set_LowerCaseExternalFilenames(Boolean)
    * Boolean get_ShortCircuit()
    * Void set_ShortCircuit(Boolean)
    * Boolean get_BigEndian()
    * Void set_BigEndian(Boolean)
    * GMAssetCompiler.eScriptKind get_DefaultCodeKind()
    * Void set_DefaultCodeKind(GMAssetCompiler.eScriptKind)
    * System.String get_BaseProject()
    * Void set_BaseProject(System.String)
    * Boolean get_ZeusProject()
    * Void set_ZeusProject(Boolean)
    * System.String get_ClangExeLocation()
    * Void set_ClangExeLocation(System.String)
    * System.String get_ClangGMLIncludeLocation()
    * Void set_ClangGMLIncludeLocation(System.String)
    * GMAssetCompiler.IFFSaver get_IFFSaver()
    * Void set_IFFSaver(GMAssetCompiler.IFFSaver)
    * GMAssetCompiler.LLVMSaver get_LLVMSaver()
    * Void set_LLVMSaver(GMAssetCompiler.LLVMSaver)
    * System.String get_LLVMSourceDir()
    * Void set_LLVMSourceDir(System.String)
    * System.String get_MacHomeDir()
    * Void set_MacHomeDir(System.String)
    * GMAssetCompiler.IniFile get_OptionsIniFile()
    * Void set_OptionsIniFile(GMAssetCompiler.IniFile)
    * Boolean get_IgnoreCache()
    * Void set_IgnoreCache(Boolean)
    * System.String get_Config()
    * Void set_Config(System.String)
    * System.String get_CacheBaseDir()
    * Void set_CacheBaseDir(System.String)
    * System.String get_TempBaseDir()
    * Void set_TempBaseDir(System.String)
    * System.String get_ProjectCacheDir()
    * Void set_ProjectCacheDir(System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Boolean StudioData
    * Int32 MakerValue
    * Int64 TargetMask
    * System.Collections.Generic.List`1[GMAssetCompiler.GMLFunctionInExtensionUsed] ExtensionFunctionsUsed
    * GMAssetCompiler.IMachineType MachineType
    * System.String OutputDir
    * Boolean WriteTextures
    * Boolean WriteWaves
    * Boolean CompileOnly
    * Boolean SplashOmit
    * Boolean SeparateOpaqueAndAlpha
    * Boolean DisplaySortedTextures
    * Int32 TexturePageWidth
    * Int32 TexturePageHeight
    * Int32 TextureScale
    * Boolean Verbose
    * Boolean CompileVerbose
    * Boolean RemoveDND
    * Boolean CenterHTML5Game
    * Boolean TargetRunner
    * Boolean NoCache
    * Boolean NoIndexHTML
    * System.String HTMLRunner
    * System.String ShaderPreamble
    * Boolean DoObfuscate
    * Boolean ObfuscateObfuscate
    * Boolean ObfuscatePrettyPrint
    * Boolean ObfuscateRemoveUnused
    * Boolean ObfuscateEncodeStrings
    * System.String LoadingBarName
    * Boolean CustomLoadingScreen
    * Int32 ExitCode
    * Boolean InhibitErrorOutput
    * System.String PreObfuscateLib
    * GMAssetCompiler.GMAssets Assets
    * Boolean Studio
    * System.String OptionsIniFileName
    * Boolean CompileToVM
    * System.String WorkingDirectory
    * Int32 Fellowship
    * Int32 Cabal
    * GMAssetCompiler.CheckLicense License
    * System.String HTML5GameFolder
    * System.Globalization.CultureInfo InvariantCulture
    * System.String FunctionsUsedOutputFile
    * System.String EducationMode
    * Boolean LowerCaseExternalFilenames
    * Boolean ShortCircuit
    * Boolean BigEndian
    * GMAssetCompiler.eScriptKind DefaultCodeKind
    * System.String BaseProject
    * Boolean ZeusProject
    * System.String ClangExeLocation
    * System.String ClangGMLIncludeLocation
    * GMAssetCompiler.IFFSaver IFFSaver
    * GMAssetCompiler.LLVMSaver LLVMSaver
    * System.String LLVMSourceDir
    * System.String MacHomeDir
    * GMAssetCompiler.IniFile OptionsIniFile
    * Boolean IgnoreCache
    * System.String Config
    * System.String CacheBaseDir
    * System.String TempBaseDir
    * System.String ProjectCacheDir
    * System.String ConfigFileName
    * Int32 MajorVersion
    * Int32 MinorVersion
    * Int32 ReleaseVersion
    * Int32 BuildVersion
    * System.String GameName
    * Boolean DebugOutput
    * Boolean BuildMetroProj
    * System.String MetroProjLocation
    * Boolean SteamProject
    * Int32 SteamAppId
    * System.String SteamLibrary
    * Int32 StudioEdition
    * Boolean Quiet
    * Boolean GenerateSWFImages
    * System.String SWFFilename
    * Single SWFPrecision
    * System.String SpineFilename
    * Boolean GenerateSpineImage
    * Boolean GetSpineRootX
    * Boolean GetSpineRootY
    * System.String PS4SDKDir
    * System.String PSVitaSDKDir
    * System.String PS3SDKDir
    * Int32 DebuggerPort
    * System.String HostIP
    * Int32 HostPort
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.Program+TextureGroup] TextureGroups
    * System.IO.TextWriter Out
    * System.IO.TextWriter Error
    * GMAssetCompiler.eTexType[] TextureType
    * Int32 kMakerMaxValue
    * GMAssetCompiler.Program+TextureGroup
    * GMAssetCompiler.Program+Del_ParallelExec`2[R,T]
# GMAssetCompiler.Program+TextureGroup
  ## Members
    * System.Collections.Generic.List`1[System.String] get_Resources()
    * Void set_Resources(System.Collections.Generic.List`1[System.String])
    * Boolean get_Scaled()
    * Void set_Scaled(Boolean)
    * Boolean get_RemoveSpace()
    * Void set_RemoveSpace(Boolean)
    * Int32 get_Border()
    * Void set_Border(Int32)
    * Int64 get_Targets()
    * Void set_Targets(Int64)
    * TextureGroup get_Parent()
    * Void set_Parent(TextureGroup)
    * System.String get_ParentName()
    * Void set_ParentName(System.String)
    * Boolean get_UseFor3D()
    * Void set_UseFor3D(Boolean)
    * System.String get_Name()
    * Void set_Name(System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.Collections.Generic.List`1[System.String], Boolean, Int32, Boolean, Int64, System.String, System.String)
    * System.Collections.Generic.List`1[System.String] Resources
    * Boolean Scaled
    * Boolean RemoveSpace
    * Int32 Border
    * Int64 Targets
    * TextureGroup Parent
    * System.String ParentName
    * Boolean UseFor3D
    * System.String Name
# GMAssetCompiler.Program+Del_ParallelExec`2[R,T]
  ## Members
    * R Invoke(T)
    * System.IAsyncResult BeginInvoke(T, System.AsyncCallback, System.Object)
    * R EndInvoke(System.IAsyncResult)
    * Void GetObjectData(System.Runtime.Serialization.SerializationInfo, System.Runtime.Serialization.StreamingContext)
    * Boolean Equals(System.Object)
    * System.Delegate[] GetInvocationList()
    * Int32 GetHashCode()
    * System.Object DynamicInvoke(System.Object[])
    * System.Reflection.MethodInfo get_Method()
    * System.Object get_Target()
    * System.Object Clone()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor(System.Object, IntPtr)
    * System.Reflection.MethodInfo Method
    * System.Object Target
# GMAssetCompiler.Properties.Resources
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
# GMAssetCompiler.Properties.Settings
  ## Members
    * GMAssetCompiler.Properties.Settings get_Default()
    * System.Configuration.SettingsContext get_Context()
    * System.Configuration.SettingsPropertyCollection get_Properties()
    * System.Configuration.SettingsPropertyValueCollection get_PropertyValues()
    * System.Configuration.SettingsProviderCollection get_Providers()
    * System.String get_SettingsKey()
    * Void set_SettingsKey(System.String)
    * Void add_PropertyChanged(System.ComponentModel.PropertyChangedEventHandler)
    * Void remove_PropertyChanged(System.ComponentModel.PropertyChangedEventHandler)
    * Void add_SettingChanging(System.Configuration.SettingChangingEventHandler)
    * Void remove_SettingChanging(System.Configuration.SettingChangingEventHandler)
    * Void add_SettingsLoaded(System.Configuration.SettingsLoadedEventHandler)
    * Void remove_SettingsLoaded(System.Configuration.SettingsLoadedEventHandler)
    * Void add_SettingsSaving(System.Configuration.SettingsSavingEventHandler)
    * Void remove_SettingsSaving(System.Configuration.SettingsSavingEventHandler)
    * System.Object GetPreviousVersion(System.String)
    * Void Reload()
    * Void Reset()
    * Void Save()
    * System.Object get_Item(System.String)
    * Void set_Item(System.String, System.Object)
    * Void Upgrade()
    * Void Initialize(System.Configuration.SettingsContext, System.Configuration.SettingsPropertyCollection, System.Configuration.SettingsProviderCollection)
    * Boolean get_IsSynchronized()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * GMAssetCompiler.Properties.Settings Default
    * System.Configuration.SettingsContext Context
    * System.Configuration.SettingsPropertyCollection Properties
    * System.Configuration.SettingsPropertyValueCollection PropertyValues
    * System.Configuration.SettingsProviderCollection Providers
    * System.String SettingsKey
    * System.Object Item [System.String]
    * Boolean IsSynchronized
    * System.ComponentModel.PropertyChangedEventHandler PropertyChanged
    * System.Configuration.SettingChangingEventHandler SettingChanging
    * System.Configuration.SettingsLoadedEventHandler SettingsLoaded
    * System.Configuration.SettingsSavingEventHandler SettingsSaving
# GMAssetCompiler.PropertyAttribute
  ## Members
    * System.String get_Name()
    * Void set_Name(System.String)
    * System.String get_Description()
    * Void set_Description(System.String)
    * System.String get_Category()
    * Void set_Category(System.String)
    * System.Object get_Default()
    * Void set_Default(System.Object)
    * Boolean get_Disabled()
    * Void set_Disabled(Boolean)
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Object get_TypeId()
    * Boolean Match(System.Object)
    * Boolean IsDefaultAttribute()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor(System.String)
    * System.String Name
    * System.String Description
    * System.String Category
    * System.Object Default
    * Boolean Disabled
    * System.Object TypeId
# Flobbster.Windows.Forms.PropertySpec
  ## Members
    * System.Attribute[] get_Attributes()
    * Void set_Attributes(System.Attribute[])
    * System.String get_Category()
    * Void set_Category(System.String)
    * System.String get_ConverterTypeName()
    * Void set_ConverterTypeName(System.String)
    * System.Object get_DefaultValue()
    * Void set_DefaultValue(System.Object)
    * System.String get_Description()
    * Void set_Description(System.String)
    * System.String get_EditorTypeName()
    * Void set_EditorTypeName(System.String)
    * System.String get_Name()
    * Void set_Name(System.String)
    * System.String get_TypeName()
    * Void set_TypeName(System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String, System.String)
    * Void .ctor(System.String, System.Type)
    * Void .ctor(System.String, System.String, System.String)
    * Void .ctor(System.String, System.Type, System.String)
    * Void .ctor(System.String, System.String, System.String, System.String)
    * Void .ctor(System.String, System.Type, System.String, System.String)
    * Void .ctor(System.String, System.String, System.String, System.String, System.Object)
    * Void .ctor(System.String, System.Type, System.String, System.String, System.Object)
    * Void .ctor(System.String, System.String, System.String, System.String, System.Object, System.String, System.String)
    * Void .ctor(System.String, System.Type, System.String, System.String, System.Object, System.String, System.String)
    * Void .ctor(System.String, System.String, System.String, System.String, System.Object, System.Type, System.String)
    * Void .ctor(System.String, System.Type, System.String, System.String, System.Object, System.Type, System.String)
    * Void .ctor(System.String, System.String, System.String, System.String, System.Object, System.String, System.Type)
    * Void .ctor(System.String, System.Type, System.String, System.String, System.Object, System.String, System.Type)
    * Void .ctor(System.String, System.String, System.String, System.String, System.Object, System.Type, System.Type)
    * Void .ctor(System.String, System.Type, System.String, System.String, System.Object, System.Type, System.Type)
    * System.Attribute[] Attributes
    * System.String Category
    * System.String ConverterTypeName
    * System.Object DefaultValue
    * System.String Description
    * System.String EditorTypeName
    * System.String Name
    * System.String TypeName
# Flobbster.Windows.Forms.PropertySpecEventArgs
  ## Members
    * Flobbster.Windows.Forms.PropertySpec get_Property()
    * System.Object get_Value()
    * Void set_Value(System.Object)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(Flobbster.Windows.Forms.PropertySpec, System.Object)
    * Flobbster.Windows.Forms.PropertySpec Property
    * System.Object Value
# Flobbster.Windows.Forms.PropertySpecEventHandler
  ## Members
    * Void Invoke(System.Object, Flobbster.Windows.Forms.PropertySpecEventArgs)
    * System.IAsyncResult BeginInvoke(System.Object, Flobbster.Windows.Forms.PropertySpecEventArgs, System.AsyncCallback, System.Object)
    * Void EndInvoke(System.IAsyncResult)
    * Void GetObjectData(System.Runtime.Serialization.SerializationInfo, System.Runtime.Serialization.StreamingContext)
    * Boolean Equals(System.Object)
    * System.Delegate[] GetInvocationList()
    * Int32 GetHashCode()
    * System.Object DynamicInvoke(System.Object[])
    * System.Reflection.MethodInfo get_Method()
    * System.Object get_Target()
    * System.Object Clone()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor(System.Object, IntPtr)
    * System.Reflection.MethodInfo Method
    * System.Object Target
# Flobbster.Windows.Forms.PropertyBag
  ## Members
    * System.String get_DefaultProperty()
    * Void set_DefaultProperty(System.String)
    * PropertySpecCollection get_Properties()
    * Void add_GetValue(Flobbster.Windows.Forms.PropertySpecEventHandler)
    * Void remove_GetValue(Flobbster.Windows.Forms.PropertySpecEventHandler)
    * Void add_SetValue(Flobbster.Windows.Forms.PropertySpecEventHandler)
    * Void remove_SetValue(Flobbster.Windows.Forms.PropertySpecEventHandler)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String DefaultProperty
    * PropertySpecCollection Properties
    * Flobbster.Windows.Forms.PropertySpecEventHandler GetValue
    * Flobbster.Windows.Forms.PropertySpecEventHandler SetValue
    * Flobbster.Windows.Forms.PropertyBag+PropertySpecCollection
# Flobbster.Windows.Forms.PropertyBag+PropertySpecCollection
  ## Members
    * Int32 get_Count()
    * Boolean get_IsFixedSize()
    * Boolean get_IsReadOnly()
    * Boolean get_IsSynchronized()
    * Flobbster.Windows.Forms.PropertySpec get_Item(Int32)
    * Void set_Item(Int32, Flobbster.Windows.Forms.PropertySpec)
    * Int32 Add(Flobbster.Windows.Forms.PropertySpec)
    * Void AddRange(Flobbster.Windows.Forms.PropertySpec[])
    * Void Clear()
    * Boolean Contains(Flobbster.Windows.Forms.PropertySpec)
    * Boolean Contains(System.String)
    * Void CopyTo(Flobbster.Windows.Forms.PropertySpec[])
    * Void CopyTo(Flobbster.Windows.Forms.PropertySpec[], Int32)
    * System.Collections.IEnumerator GetEnumerator()
    * Int32 IndexOf(Flobbster.Windows.Forms.PropertySpec)
    * Int32 IndexOf(System.String)
    * Void Insert(Int32, Flobbster.Windows.Forms.PropertySpec)
    * Void Remove(Flobbster.Windows.Forms.PropertySpec)
    * Void Remove(System.String)
    * Void RemoveAt(Int32)
    * Flobbster.Windows.Forms.PropertySpec[] ToArray()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 Count
    * Boolean IsFixedSize
    * Boolean IsReadOnly
    * Boolean IsSynchronized
    * Flobbster.Windows.Forms.PropertySpec Item [Int32]
# Flobbster.Windows.Forms.PropertyBag+PropertySpecDescriptor
  ## Members
    * System.Type get_ComponentType()
    * Boolean get_IsReadOnly()
    * System.Type get_PropertyType()
    * Boolean CanResetValue(System.Object)
    * System.Object GetValue(System.Object)
    * Void ResetValue(System.Object)
    * Void SetValue(System.Object, System.Object)
    * Boolean ShouldSerializeValue(System.Object)
    * System.ComponentModel.TypeConverter get_Converter()
    * Boolean get_IsLocalizable()
    * System.ComponentModel.DesignerSerializationVisibility get_SerializationVisibility()
    * Void AddValueChanged(System.Object, System.EventHandler)
    * Boolean Equals(System.Object)
    * System.ComponentModel.PropertyDescriptorCollection GetChildProperties()
    * System.ComponentModel.PropertyDescriptorCollection GetChildProperties(System.Attribute[])
    * System.ComponentModel.PropertyDescriptorCollection GetChildProperties(System.Object)
    * System.ComponentModel.PropertyDescriptorCollection GetChildProperties(System.Object, System.Attribute[])
    * System.Object GetEditor(System.Type)
    * Int32 GetHashCode()
    * Void RemoveValueChanged(System.Object, System.EventHandler)
    * Boolean get_SupportsChangeEvents()
    * System.ComponentModel.AttributeCollection get_Attributes()
    * System.String get_Category()
    * System.String get_Description()
    * Boolean get_IsBrowsable()
    * System.String get_Name()
    * Boolean get_DesignTimeOnly()
    * System.String get_DisplayName()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor(Flobbster.Windows.Forms.PropertySpec, Flobbster.Windows.Forms.PropertyBag, System.String, System.Attribute[])
    * System.Type ComponentType
    * Boolean IsReadOnly
    * System.Type PropertyType
    * System.ComponentModel.TypeConverter Converter
    * Boolean IsLocalizable
    * System.ComponentModel.DesignerSerializationVisibility SerializationVisibility
    * Boolean SupportsChangeEvents
    * System.ComponentModel.AttributeCollection Attributes
    * System.String Category
    * System.String Description
    * Boolean IsBrowsable
    * System.String Name
    * Boolean DesignTimeOnly
    * System.String DisplayName
# Flobbster.Windows.Forms.PropertyTable
  ## Members
    * System.Object get_Item(System.String)
    * Void set_Item(System.String, System.Object)
    * System.String get_DefaultProperty()
    * Void set_DefaultProperty(System.String)
    * PropertySpecCollection get_Properties()
    * Void add_GetValue(Flobbster.Windows.Forms.PropertySpecEventHandler)
    * Void remove_GetValue(Flobbster.Windows.Forms.PropertySpecEventHandler)
    * Void add_SetValue(Flobbster.Windows.Forms.PropertySpecEventHandler)
    * Void remove_SetValue(Flobbster.Windows.Forms.PropertySpecEventHandler)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Object Item [System.String]
    * System.String DefaultProperty
    * PropertySpecCollection Properties
    * Flobbster.Windows.Forms.PropertySpecEventHandler GetValue
    * Flobbster.Windows.Forms.PropertySpecEventHandler SetValue
# GMAssetCompiler.eExtraFileType
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.eExtraFileType eEFT_Included
    * GMAssetCompiler.eExtraFileType eEFT_Extension
    * GMAssetCompiler.eExtraFileType eEFT_Unknown
# GMAssetCompiler.ExtraFile
  ## Members
    * System.String get_SourceFileName()
    * Void set_SourceFileName(System.String)
    * System.String get_DestFileName()
    * Void set_DestFileName(System.String)
    * GMAssetCompiler.eExtraFileType get_Type()
    * Void set_Type(GMAssetCompiler.eExtraFileType)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String)
    * Void .ctor(System.String, GMAssetCompiler.eExtraFileType)
    * System.String SourceFileName
    * System.String DestFileName
    * GMAssetCompiler.eExtraFileType Type
# GMAssetCompiler.IFFSaver
  ## Members
    * Void Save(GMAssetCompiler.GMAssets, System.String)
    * Void WriteExtensionsToIniFile(GMAssetCompiler.GMAssets)
    * Void WriteiOSProject(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.List`1[GMAssetCompiler.ExtraFile])
    * Void WriteCode(System.Collections.Generic.IList`1[GMAssetCompiler.GML2VM], System.IO.Stream, GMAssetCompiler.IFF)
    * Void WriteVARI(System.Collections.Generic.IList`1[GMAssetCompiler.GML2VM], System.IO.Stream, GMAssetCompiler.IFF)
    * Void WriteFUNC(System.Collections.Generic.IList`1[GMAssetCompiler.GML2VM], System.IO.Stream, GMAssetCompiler.IFF)
    * Void WriteDebugScripts(System.Collections.Generic.IList`1[GMAssetCompiler.GML2VM], System.IO.Stream, GMAssetCompiler.IFF)
    * Void WriteDebugLocalVariables(System.Collections.Generic.IList`1[GMAssetCompiler.GML2VM], System.IO.Stream, GMAssetCompiler.IFF)
    * Void WriteDebugInfo(System.Collections.Generic.IList`1[GMAssetCompiler.GML2VM], System.IO.Stream, GMAssetCompiler.IFF)
    * Void WriteDebugInstNames(System.Collections.Generic.IList`1[System.String], System.IO.Stream, GMAssetCompiler.IFF)
    * Void ParseGMLFile(GMAssetCompiler.GMExtension, GMAssetCompiler.GMExtensionInclude, System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.GMExtensionFunction])
    * Boolean CompileAllCode(GMAssetCompiler.GMAssets)
    * Void SaveDebugInfo(GMAssetCompiler.GMAssets, System.IO.Stream)
    * Void SaveAudioGroups(GMAssetCompiler.GMAssets, System.Collections.Generic.List`1[GMAssetCompiler.ExtraFile])
    * Void Save(GMAssetCompiler.GMAssets, System.IO.Stream, System.Collections.Generic.List`1[GMAssetCompiler.ExtraFile], System.Collections.Generic.Dictionary`2[System.String,System.UInt32])
    * Void WriteDataList[T](System.Collections.Generic.IList`1[T], System.IO.Stream, GMAssetCompiler.IFF, WriteDelegate`1)
    * Int32 GetCompiledCodeIndex(Int32)
    * Void Get1stRoomSize(GMAssetCompiler.GMAssets, Int32 ByRef, Int32 ByRef)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
# GMAssetCompiler.IFFSaver+IFFSaverCodeEntry
  ## Members
    * GMAssetCompiler.GML2VM get_Code()
    * Void set_Code(GMAssetCompiler.GML2VM)
    * Int64 get_Offset()
    * Void set_Offset(Int64)
    * Int64 get_Length()
    * Void set_Length(Int64)
    * Int32 get_NumLocals()
    * Void set_NumLocals(Int32)
    * Int32 get_NumArguments()
    * Void set_NumArguments(Int32)
    * System.String get_Name()
    * Void set_Name(System.String)
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * GMAssetCompiler.GML2VM Code
    * Int64 Offset
    * Int64 Length
    * Int32 NumLocals
    * Int32 NumArguments
    * System.String Name
# GMAssetCompiler.eSquishFlags
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.eSquishFlags kDxt1
    * GMAssetCompiler.eSquishFlags kDxt3
    * GMAssetCompiler.eSquishFlags kDxt5
    * GMAssetCompiler.eSquishFlags kColourClusterFit
    * GMAssetCompiler.eSquishFlags kColourRangeFit
    * GMAssetCompiler.eSquishFlags kColourMetricPerceptual
    * GMAssetCompiler.eSquishFlags kColourMetricUniform
    * GMAssetCompiler.eSquishFlags kWeightColourByAlpha
    * GMAssetCompiler.eSquishFlags kClusterFitMaxIterationBit
    * GMAssetCompiler.eSquishFlags kClusterFitMaxIteration
    * GMAssetCompiler.eSquishFlags kClusterFitMaxIterationMask
    * GMAssetCompiler.eSquishFlags kClusterFitMaxIteration1
    * GMAssetCompiler.eSquishFlags kClusterFitMaxIteration2
    * GMAssetCompiler.eSquishFlags kClusterFitMaxIteration3
    * GMAssetCompiler.eSquishFlags kClusterFitMaxIteration4
    * GMAssetCompiler.eSquishFlags kClusterFitMaxIteration5
    * GMAssetCompiler.eSquishFlags kClusterFitMaxIteration6
    * GMAssetCompiler.eSquishFlags kClusterFitMaxIteration7
    * GMAssetCompiler.eSquishFlags kClusterFitMaxIteration8
# GMAssetCompiler.eSquishCPU
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * GMAssetCompiler.eSquishCPU kNone
    * GMAssetCompiler.eSquishCPU kFPU
    * GMAssetCompiler.eSquishCPU kSSE1
    * GMAssetCompiler.eSquishCPU kSSE2
    * GMAssetCompiler.eSquishCPU kALTIVEC
# GMAssetCompiler.DDS
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * UInt32 DDSD_CAPS
    * UInt32 DDSD_HEIGHT
    * UInt32 DDSD_WIDTH
    * UInt32 DDSD_PITCH
    * UInt32 DDSD_PIXELFORMAT
    * UInt32 DDSD_MIPMAPCOUNT
    * UInt32 DDSD_LINEARSIZE
    * UInt32 DDSD_DEPTH
    * UInt32 DDPF_ALPHAPIXELS
    * UInt32 DDPF_FOURCC
    * UInt32 DDPF_RGB
    * UInt32 DDSCAPS_COMPLEX
    * UInt32 DDSCAPS_TEXTURE
    * UInt32 DDSCAPS_MIPMAP
    * UInt32 DDSCAPS2_CUBEMAP
    * UInt32 DDSCAPS2_CUBEMAP_POSITIVEX
    * UInt32 DDSCAPS2_CUBEMAP_NEGATIVEX
    * UInt32 DDSCAPS2_CUBEMAP_POSITIVEY
    * UInt32 DDSCAPS2_CUBEMAP_NEGATIVEY
    * UInt32 DDSCAPS2_CUBEMAP_POSITIVEZ
    * UInt32 DDSCAPS2_CUBEMAP_NEGATIVEZ
    * UInt32 DDSCAPS2_VOLUME
    * GMAssetCompiler.DDS+SDDPIXELFORMAT
    * GMAssetCompiler.DDS+SDDCAPS2
    * GMAssetCompiler.DDS+SDDSHeader
# GMAssetCompiler.DDS+SDDPIXELFORMAT
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * UInt32 dwSize
    * UInt32 dwFlags
    * UInt32 dwFourCC
    * UInt32 dwRGBBitCount
    * UInt32 dwRBitMask
    * UInt32 dwGBitMask
    * UInt32 dwBBitMask
    * UInt32 dwRGBAlphaBitMask
# GMAssetCompiler.DDS+SDDCAPS2
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * UInt32 dwCaps1
    * UInt32 dwCaps2
    * UInt32 Reserved1
    * UInt32 Reserved2
# GMAssetCompiler.DDS+SDDSHeader
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * UInt32 Magic
    * UInt32 dwSize
    * UInt32 dwFlags
    * UInt32 dwHeight
    * UInt32 dwWidth
    * UInt32 dwPitchOrLinearSize
    * UInt32 dwDepth
    * UInt32 dwMipMapCount
    * UInt32 dwReserved1
    * UInt32 dwReserved1_2
    * UInt32 dwReserved1_3
    * UInt32 dwReserved1_4
    * UInt32 dwReserved1_5
    * UInt32 dwReserved1_6
    * UInt32 dwReserved1_7
    * UInt32 dwReserved1_8
    * UInt32 dwReserved1_9
    * UInt32 dwReserved1_10
    * UInt32 dwReserved1_11
    * SDDPIXELFORMAT ddpfPixelFormat
    * SDDCAPS2 ddsCaps
    * UInt32 dwReserved2
# GMAssetCompiler.Squish
  ## Members
    * GMAssetCompiler.eSquishCPU GetCPUCaps()
    * Void Compress(IntPtr, IntPtr, GMAssetCompiler.eSquishFlags)
    * Void CompressMasked(IntPtr, Int32, IntPtr, GMAssetCompiler.eSquishFlags)
    * Void Decompress(IntPtr, IntPtr, GMAssetCompiler.eSquishFlags)
    * Int32 GetStorageRequirements(Int32, Int32, GMAssetCompiler.eSquishFlags)
    * Void CompressImage(IntPtr, Int32, Int32, IntPtr, GMAssetCompiler.eSquishFlags)
    * Void DecompressImage(IntPtr, Int32, Int32, IntPtr, GMAssetCompiler.eSquishFlags)
    * Void CompressPVRTC(IntPtr, Int32, Int32, IntPtr, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
# GMAssetCompiler.StreamHelper
  ## Members
    * Int16 ReadShort(System.IO.Stream)
    * Int32 ReadInteger(System.IO.Stream)
    * Int64 ReadLong(System.IO.Stream)
    * Boolean ReadBoolean(System.IO.Stream)
    * System.String ReadString(System.IO.Stream)
    * System.Drawing.Image ReadBitmap(System.IO.Stream)
    * System.Guid ReadGuid(System.IO.Stream)
    * Byte[] ReadCompressedStream(System.IO.Stream)
    * System.IO.Stream ReadStreamC(System.IO.Stream)
    * System.IO.Stream ReadStreamE(System.IO.Stream)
    * Byte[] ReadStream(System.IO.Stream)
    * Single ReadSingle(System.IO.Stream)
    * Double ReadDouble(System.IO.Stream)
    * Void WriteInteger(System.IO.Stream, Int32)
    * Void WriteShort(System.IO.Stream, Int16)
    * Void WriteGUID(System.IO.Stream, System.Guid)
    * Void WriteLong(System.IO.Stream, Int64)
    * Void WriteBoolean(System.IO.Stream, Boolean)
    * Void WriteChunk(System.IO.Stream, System.String)
    * Int64 WriteChunkSize(System.IO.Stream)
    * Void PatchChunkSize(System.IO.Stream, Int64)
    * Void PatchOffset(System.IO.Stream, Int64)
    * Void WriteString(System.IO.Stream, System.String)
    * Void WriteDouble(System.IO.Stream, Double)
    * Void WriteSingle(System.IO.Stream, Single)
    * Void Align(System.IO.Stream, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
# GMAssetCompiler.Texture
  ## Members
    * System.Drawing.Bitmap get_Bitmap()
    * Void set_Bitmap(System.Drawing.Bitmap)
    * Int32 get_GridSizeX()
    * Int32 get_GridSizeY()
    * Int32 get_AreaFree()
    * Int32 get_TP()
    * Void set_TP(Int32)
    * Int32 get_Group()
    * Void set_Group(Int32)
    * Int32 get_Scale()
    * Void set_Scale(Int32)
    * System.Collections.Generic.List`1[GMAssetCompiler.TexturePageEntry] get_Entries()
    * System.String get_Name()
    * Void set_Name(System.String)
    * Byte[] get_BitmapPNGData()
    * Void set_BitmapPNGData(Byte[])
    * Void Resize(Int32, Int32)
    * System.Drawing.Bitmap ResizeImage(System.Drawing.Bitmap, Int32, Int32)
    * Boolean Alloc(GMAssetCompiler.TexturePageEntry, Int32 ByRef, Int32 ByRef)
    * Void CopyEntries()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(Byte[], Int32)
    * Void .ctor(Int32, Int32, Int32, Int32, Int32, Int32, Int32)
    * System.Drawing.Bitmap Bitmap
    * Int32 GridSizeX
    * Int32 GridSizeY
    * Int32 AreaFree
    * Int32 TP
    * Int32 Group
    * Int32 Scale
    * System.Collections.Generic.List`1[GMAssetCompiler.TexturePageEntry] Entries
    * System.String Name
    * Byte[] BitmapPNGData
    * GMAssetCompiler.yyRect TextureRects
# GMAssetCompiler.TextureGroup
  ## Members
    * System.String get_Name()
    * Void set_Name(System.String)
    * System.Collections.Generic.List`1[GMAssetCompiler.Texture] get_Textures()
    * Void set_Textures(System.Collections.Generic.List`1[GMAssetCompiler.Texture])
    * System.Collections.Generic.List`1[GMAssetCompiler.TexturePageEntry] get_Entries()
    * Void set_Entries(System.Collections.Generic.List`1[GMAssetCompiler.TexturePageEntry])
    * Void LoadCacheFile(System.String)
    * Void SaveCacheFile(System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String)
    * System.String Name
    * System.Collections.Generic.List`1[GMAssetCompiler.Texture] Textures
    * System.Collections.Generic.List`1[GMAssetCompiler.TexturePageEntry] Entries
# GMAssetCompiler.TexturePage
  ## Members
    * System.Collections.Generic.List`1[GMAssetCompiler.TexturePageEntry] get_Entries()
    * System.Collections.Generic.IEnumerable`1[GMAssetCompiler.Texture] get_Textures()
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.TextureGroup] get_TextureGroups()
    * TextureGroup get_CurrentGroup()
    * Void set_CurrentGroup(TextureGroup)
    * Int32 get_MarginX()
    * Int32 get_MarginY()
    * Int32 get_GapX()
    * Int32 get_GapY()
    * Int32 get_TextureSizeWidth()
    * Int32 get_TextureSizeHeight()
    * Void Reset()
    * System.String BeginGroup(System.String)
    * Void EndGroup()
    * System.Drawing.Bitmap Scale(System.Drawing.Bitmap, Int32, Int32)
    * GMAssetCompiler.TexturePageEntry AddImage(System.String, Boolean, Boolean, Int32, System.String, System.String)
    * GMAssetCompiler.TexturePageEntry AddImage(System.Drawing.Bitmap, Boolean, Boolean, System.String, Int32, System.String)
    * Void Compile()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(Int32, Int32, Int32, Int32, Int32, Int32)
    * System.Collections.Generic.List`1[GMAssetCompiler.TexturePageEntry] Entries
    * System.Collections.Generic.IEnumerable`1[GMAssetCompiler.Texture] Textures
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.TextureGroup] TextureGroups
    * TextureGroup CurrentGroup
    * Int32 MarginX
    * Int32 MarginY
    * Int32 GapX
    * Int32 GapY
    * Int32 TextureSizeWidth
    * Int32 TextureSizeHeight
# GMAssetCompiler.TexturePageEntry
  ## Members
    * Int32 get_Entry()
    * Void set_Entry(Int32)
    * UInt32 get_Hash()
    * Void set_Hash(UInt32)
    * System.String get_CacheFileName()
    * Void set_CacheFileName(System.String)
    * System.String get_BitmapFileName()
    * Void set_BitmapFileName(System.String)
    * System.String get_DebugName()
    * Void set_DebugName(System.String)
    * GMAssetCompiler.TexturePageEntry get_SameAs()
    * Void set_SameAs(GMAssetCompiler.TexturePageEntry)
    * System.Drawing.Bitmap get_Bitmap()
    * Void set_Bitmap(System.Drawing.Bitmap)
    * System.String get_Name()
    * Void set_Name(System.String)
    * Int32 get_X()
    * Void set_X(Int32)
    * Int32 get_Y()
    * Void set_Y(Int32)
    * GMAssetCompiler.Texture get_TP()
    * Void set_TP(GMAssetCompiler.Texture)
    * Int32 get_W()
    * Void set_W(Int32)
    * Int32 get_H()
    * Void set_H(Int32)
    * Int32 get_XOffset()
    * Void set_XOffset(Int32)
    * Int32 get_YOffset()
    * Void set_YOffset(Int32)
    * Int32 get_CropWidth()
    * Void set_CropWidth(Int32)
    * Int32 get_CropHeight()
    * Void set_CropHeight(Int32)
    * Int32 get_OW()
    * Void set_OW(Int32)
    * Int32 get_OH()
    * Void set_OH(Int32)
    * Boolean get_DebugTag()
    * Void set_DebugTag(Boolean)
    * Boolean get_RepeatBorder()
    * Void set_RepeatBorder(Boolean)
    * Boolean get_OriginalRepeatBorder()
    * Void set_OriginalRepeatBorder(Boolean)
    * Boolean get_IgnoreRepeatBorder()
    * Void set_IgnoreRepeatBorder(Boolean)
    * Boolean get_TileH()
    * Void set_TileH(Boolean)
    * Boolean get_TileV()
    * Void set_TileV(Boolean)
    * Int32 get_BorderWidthV()
    * Void set_BorderWidthV(Int32)
    * Int32 get_BorderWidthH()
    * Void set_BorderWidthH(Int32)
    * Boolean get_HasAlpha()
    * Void set_HasAlpha(Boolean)
    * Boolean get_LeaveBorderEmpty()
    * Void set_LeaveBorderEmpty(Boolean)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(System.Drawing.Bitmap, UInt32)
    * Void .ctor(System.Drawing.Bitmap, System.String, UInt32)
    * Int32 Entry
    * UInt32 Hash
    * System.String CacheFileName
    * System.String BitmapFileName
    * System.String DebugName
    * GMAssetCompiler.TexturePageEntry SameAs
    * System.Drawing.Bitmap Bitmap
    * System.String Name
    * Int32 X
    * Int32 Y
    * GMAssetCompiler.Texture TP
    * Int32 W
    * Int32 H
    * Int32 XOffset
    * Int32 YOffset
    * Int32 CropWidth
    * Int32 CropHeight
    * Int32 OW
    * Int32 OH
    * Boolean DebugTag
    * Boolean RepeatBorder
    * Boolean OriginalRepeatBorder
    * Boolean IgnoreRepeatBorder
    * Boolean TileH
    * Boolean TileV
    * Int32 BorderWidthV
    * Int32 BorderWidthH
    * Boolean HasAlpha
    * Boolean LeaveBorderEmpty
    * Int32 ms_count
# GMAssetCompiler.VAG
  ## Members
    * Void memset(Void*, Byte, UInt32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 NUM_SAMPLES_IN_VAG_PACKET
    * Int32 NUM_BYTES_IN_VAG_PACKET
    * UInt32 AUDIO_SAMP_BITS_MASK
    * Int32 AUDIO_SAMP_BITS_SHFT
    * UInt32 AUDIO_SAMP_FMT_MASK
    * UInt32 AUDIO_FMT_VAG
    * Int32 AUDIO_SAMP_FMT_SHFT
    * Int32 ERR_OK
# GMAssetCompiler.View`1[T]
  ## Members
    * Flobbster.Windows.Forms.PropertyBag Prepare()
    * System.Drawing.Image PrepareImage()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(T)
# GMAssetCompiler.ViewBackground
  ## Members
    * System.Drawing.Image PrepareImage()
    * Flobbster.Windows.Forms.PropertyBag Prepare()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMBackground)
# GMAssetCompiler.ViewFont
  ## Members
    * System.Drawing.Image PrepareImage()
    * Flobbster.Windows.Forms.PropertyBag Prepare()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMFont)
# GMAssetCompiler.ViewSprite
  ## Members
    * System.Drawing.Image PrepareImage()
    * Flobbster.Windows.Forms.PropertyBag Prepare()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMSprite)
# GMAssetCompiler.Wave
  ## Members
    * Boolean get_Valid()
    * Void set_Valid(Boolean)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.IFF, Byte[], System.String, Boolean)
    * Boolean Valid
    * Byte[] RawWavFile
    * System.String FileName
    * GMAssetCompiler.Wave+SRIFF
# GMAssetCompiler.Wave+SRIFF
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * UInt32 ChunkID
    * UInt32 ChunkSize
    * UInt32 Format
    * UInt32 SubChunk1ID
    * UInt32 SubChunk1Size
    * Int16 AudioFormat
    * Int16 NumChannels
    * UInt32 SampleRate
    * UInt32 ByteRate
    * Int16 BlockAlign
    * Int16 BitsPerSample
    * UInt32 SubChunk2ID
    * UInt32 SubChunk2Size
# GMAssetCompiler.yyRect
  ## Members
    * Int32 get_top()
    * Int32 get_left()
    * Int32 get_bottom()
    * Int32 get_right()
    * Int32 get_area()
    * System.String ToString()
    * GMAssetCompiler.yyRect Create(Int32, Int32)
    * GMAssetCompiler.yyRect Test(Int32, Int32)
    * Void CompactList()
    * System.Drawing.Point AddImage(GMAssetCompiler.yyRect, Int32, Int32)
    * Void Draw(System.Drawing.Graphics, Int32, Int32)
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(Int32, Int32, Int32, Int32)
    * Int32 top
    * Int32 left
    * Int32 bottom
    * Int32 right
    * Int32 area
    * UInt64 CRC
    * Boolean packflag
    * Boolean full
    * UInt16 x
    * UInt16 y
    * UInt16 width
    * UInt16 height
    * Int32 arealeft
    * System.Collections.Generic.List`1[GMAssetCompiler.yyRect] Children
# SmartAssembly.Attributes.DoNotCaptureVariablesAttribute
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Object get_TypeId()
    * Boolean Match(System.Object)
    * Boolean IsDefaultAttribute()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor()
    * System.Object TypeId
# SmartAssembly.Attributes.DoNotCaptureAttribute
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Object get_TypeId()
    * Boolean Match(System.Object)
    * Boolean IsDefaultAttribute()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor()
    * System.Object TypeId
# SmartAssembly.Attributes.DoNotObfuscateAttribute
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Object get_TypeId()
    * Boolean Match(System.Object)
    * Boolean IsDefaultAttribute()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor()
    * System.Object TypeId
# SmartAssembly.Attributes.DoNotObfuscateTypeAttribute
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Object get_TypeId()
    * Boolean Match(System.Object)
    * Boolean IsDefaultAttribute()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor()
    * System.Object TypeId
# SmartAssembly.Attributes.DoNotPruneAttribute
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Object get_TypeId()
    * Boolean Match(System.Object)
    * Boolean IsDefaultAttribute()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor()
    * System.Object TypeId
# SmartAssembly.Attributes.DoNotPruneTypeAttribute
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Object get_TypeId()
    * Boolean Match(System.Object)
    * Boolean IsDefaultAttribute()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor()
    * System.Object TypeId
# SmartAssembly.Attributes.DoNotSealTypeAttribute
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Object get_TypeId()
    * Boolean Match(System.Object)
    * Boolean IsDefaultAttribute()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor()
    * System.Object TypeId
# SmartAssembly.Attributes.ReportExceptionAttribute
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Object get_TypeId()
    * Boolean Match(System.Object)
    * Boolean IsDefaultAttribute()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor()
    * System.Object TypeId
# SmartAssembly.Attributes.ReportUsageAttribute
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Object get_TypeId()
    * Boolean Match(System.Object)
    * Boolean IsDefaultAttribute()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(System.String)
    * System.Object TypeId
# SmartAssembly.Attributes.ObfuscateControlFlowAttribute
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Object get_TypeId()
    * Boolean Match(System.Object)
    * Boolean IsDefaultAttribute()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor()
    * System.Object TypeId
# SmartAssembly.Attributes.DoNotObfuscateControlFlowAttribute
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Object get_TypeId()
    * Boolean Match(System.Object)
    * Boolean IsDefaultAttribute()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor()
    * System.Object TypeId
# SmartAssembly.Attributes.ObfuscateToAttribute
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Object get_TypeId()
    * Boolean Match(System.Object)
    * Boolean IsDefaultAttribute()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor(System.String)
    * System.Object TypeId
# SmartAssembly.Attributes.ObfuscateNamespaceToAttribute
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Object get_TypeId()
    * Boolean Match(System.Object)
    * Boolean IsDefaultAttribute()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor(System.String)
    * System.Object TypeId
# SmartAssembly.Attributes.DoNotEncodeStringsAttribute
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Object get_TypeId()
    * Boolean Match(System.Object)
    * Boolean IsDefaultAttribute()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor()
    * System.Object TypeId
# SmartAssembly.Attributes.EncodeStringsAttribute
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Object get_TypeId()
    * Boolean Match(System.Object)
    * Boolean IsDefaultAttribute()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor()
    * System.Object TypeId
# SmartAssembly.Attributes.ExcludeFromMemberRefsProxyAttribute
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Object get_TypeId()
    * Boolean Match(System.Object)
    * Boolean IsDefaultAttribute()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor()
    * System.Object TypeId
# SmartAssembly.Attributes.StayPublicAttribute
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Object get_TypeId()
    * Boolean Match(System.Object)
    * Boolean IsDefaultAttribute()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor()
    * System.Object TypeId
# SmartAssembly.Attributes.DoNotMoveAttribute
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Object get_TypeId()
    * Boolean Match(System.Object)
    * Boolean IsDefaultAttribute()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor()
    * System.Object TypeId
# SmartAssembly.Attributes.DoNotMoveMethodsAttribute
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Object get_TypeId()
    * Boolean Match(System.Object)
    * Boolean IsDefaultAttribute()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor()
    * System.Object TypeId
# GMAssetCompiler.Spine.SkeletonRenderer
  ## Members
    * Int32[] GetRootBoneLocation(Spine.Skeleton)
    * Void GenerateImage(Spine.Skeleton, System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
# GMAssetCompiler.Spine.SkeletonRenderer+TexturedPoint
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(Single, Single, Single, Single)
    * Single x
    * Single y
    * Single u
    * Single v
# GMAssetCompiler.Spine.SkeletonRenderer+Rect
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(Single, Single, Single, Single)
    * Single left
    * Single top
    * Single right
    * Single bottom
# Spine.SpineTextureLoader
  ## Members
    * Int32 get_Width()
    * Int32 get_Height()
    * Void Load(Spine.AtlasPage, System.String)
    * Void Unload(System.Object)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 Width
    * Int32 Height
# SWFReader.eBitmapType
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * SWFReader.eBitmapType eJPEGNoHeader
    * SWFReader.eBitmapType eJPEG
    * SWFReader.eBitmapType eJPEGWithAlpha
    * SWFReader.eBitmapType ePNG
    * SWFReader.eBitmapType eGIF
    * SWFReader.eBitmapType eLossless8bit
    * SWFReader.eBitmapType eLossless15bit
    * SWFReader.eBitmapType eLossless24bit
    * SWFReader.eBitmapType eLossless8bitA
    * SWFReader.eBitmapType eLossless32bit
# SWFReader.eLosslessFormat
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * SWFReader.eLosslessFormat eLossless8bit
    * SWFReader.eLosslessFormat eLossless15bit
    * SWFReader.eLosslessFormat eLossless24bit
    * SWFReader.eLosslessFormat eLossless32bit
# SWFReader.DictionaryItem
  ## Members
    * SWFReader.eDictionaryItemType get_type()
    * Void set_type(SWFReader.eDictionaryItemType)
    * Int32 get_Id()
    * Void set_Id(Int32)
    * Void Write(System.IO.Stream)
    * Void CalculateBounds(SWFReader.Matrix33, Int32 ByRef, Int32 ByRef, Int32 ByRef, Int32 ByRef)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(SWFReader.DictionaryItem)
    * SWFReader.eDictionaryItemType type
    * Int32 Id
# SWFReader.Bitmap
  ## Members
    * SWFReader.eBitmapType get_bitmaptype()
    * Void set_bitmaptype(SWFReader.eBitmapType)
    * Byte[] get_imagedata()
    * Void set_imagedata(Byte[])
    * Byte[] get_alphadata()
    * Void set_alphadata(Byte[])
    * Byte[] get_colourtabledata()
    * Void set_colourtabledata(Byte[])
    * Int32 get_width()
    * Void set_width(Int32)
    * Int32 get_height()
    * Void set_height(Int32)
    * Void SetImageData(Byte[])
    * Void SetImageData(SWFReader.SWFRGB15[])
    * Void SetImageData(SWFReader.SWFRGB[])
    * Void SetImageData(SWFReader.SWFRGBA[])
    * Void SetAlphaData(Byte[])
    * Void SetColourTableData(SWFReader.SWFRGB[])
    * Void SetColourTableData(SWFReader.SWFRGBA[])
    * Void Write(System.IO.Stream)
    * Void CalculateBounds(SWFReader.Matrix33, Int32 ByRef, Int32 ByRef, Int32 ByRef, Int32 ByRef)
    * SWFReader.eDictionaryItemType get_type()
    * Void set_type(SWFReader.eDictionaryItemType)
    * Int32 get_Id()
    * Void set_Id(Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(SWFReader.Bitmap)
    * SWFReader.eBitmapType bitmaptype
    * Byte[] imagedata
    * Byte[] alphadata
    * Byte[] colourtabledata
    * Int32 width
    * Int32 height
    * SWFReader.eDictionaryItemType type
    * Int32 Id
# SWFReader.Vec2f
  ## Members
    * Single get_X()
    * Void set_X(Single)
    * Single get_Y()
    * Void set_Y(Single)
    * Boolean Normalise()
    * Single Dot(SWFReader.Vec2f)
    * Single Length()
    * Boolean Equals(SWFReader.Vec2f)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(Single, Single)
    * Void .ctor(Int32, Int32)
    * Void .ctor(SWFReader.Vec2f)
    * Single X
    * Single Y
# SWFReader.CollisionMask
  ## Members
    * Byte[] get_data()
    * Void set_data(Byte[])
    * Int32 get_width()
    * Void set_width(Int32)
    * Int32 get_height()
    * Void set_height(Int32)
    * Int32 get_bboxleft()
    * Void set_bboxleft(Int32)
    * Int32 get_bboxright()
    * Void set_bboxright(Int32)
    * Int32 get_bboxtop()
    * Void set_bboxtop(Int32)
    * Int32 get_bboxbottom()
    * Void set_bboxbottom(Int32)
    * Byte[] get_rledata()
    * Void set_rledata(Byte[])
    * Void Write(System.IO.Stream)
    * Void RasteriseTri(SWFReader.Vec2f[])
    * Int32 DoRLECompression(Byte[], Byte[], Int32)
    * Int32 DoExpRLECompression(Byte[], Byte[], Int32)
    * Void GenerateCompressedMask()
    * Void GenerateFromFrame(SWFReader.TimelineFrame, System.Collections.Generic.List`1[SWFReader.DictionaryItem], Int32, Int32, Single, Int32, Int32, Int32, Int32, Int32, Int32)
    * Void GenerateFromMergedMasks(System.Collections.Generic.List`1[SWFReader.CollisionMask])
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Byte[] data
    * Int32 width
    * Int32 height
    * Int32 bboxleft
    * Int32 bboxright
    * Int32 bboxtop
    * Int32 bboxbottom
    * Byte[] rledata
# SWFReader.eDictionaryItemType
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * SWFReader.eDictionaryItemType eInvalid
    * SWFReader.eDictionaryItemType eShape
    * SWFReader.eDictionaryItemType eBitmap
    * SWFReader.eDictionaryItemType eFont
    * SWFReader.eDictionaryItemType eTextField
    * SWFReader.eDictionaryItemType eSprite
# SWFReader.eDLTag
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * SWFReader.eDLTag ePlace
    * SWFReader.eDLTag eShowFrame
# SWFReader.ColTransform
  ## Members
    * Int32[] get_colmul()
    * Void set_colmul(Int32[])
    * Int32[] get_coladd()
    * Void set_coladd(Int32[])
    * SWFReader.ColTransform Mult(SWFReader.ColTransform, SWFReader.ColTransform)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(Int32, Int32, Int32, Int32, Int32, Int32, Int32, Int32)
    * Void .ctor(SWFReader.ColTransform)
    * Int32[] colmul
    * Int32[] coladd
# SWFReader.DLEntry
  ## Members
    * SWFReader.eDLTag get_Tag()
    * Void set_Tag(SWFReader.eDLTag)
    * SWFReader.Matrix33 get_Matrix()
    * Void set_Matrix(SWFReader.Matrix33)
    * Int32 get_Id()
    * Void set_Id(Int32)
    * Int32 get_Depth()
    * Void set_Depth(Int32)
    * Int32 get_ClipDepth()
    * Void set_ClipDepth(Int32)
    * SWFReader.ColTransform get_ColTrans()
    * Void set_ColTrans(SWFReader.ColTransform)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(SWFReader.eDLTag, SWFReader.Matrix33, Int32, Int32, Int32, SWFReader.ColTransform)
    * Void .ctor(SWFReader.DLEntry)
    * SWFReader.eDLTag Tag
    * SWFReader.Matrix33 Matrix
    * Int32 Id
    * Int32 Depth
    * Int32 ClipDepth
    * SWFReader.ColTransform ColTrans
# SWFReader.DisplayList
  ## Members
    * System.Collections.Generic.List`1[SWFReader.DLEntry] get_Entries()
    * Void set_Entries(System.Collections.Generic.List`1[SWFReader.DLEntry])
    * Void AddPlace(Int32, Int32, Int32, SWFReader.Matrix33, SWFReader.ColTransform)
    * Void AddShowFrame()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.List`1[SWFReader.DLEntry] Entries
# SWFReader.eFillStyleType
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * SWFReader.eFillStyleType eInvalid
    * SWFReader.eFillStyleType eSolid
    * SWFReader.eFillStyleType eGradient
    * SWFReader.eFillStyleType eBitmap
# SWFReader.FillStyleData
  ## Members
    * SWFReader.eFillStyleType get_type()
    * Void set_type(SWFReader.eFillStyleType)
    * Boolean Matches(SWFReader.FillStyleData)
    * Void Write(System.IO.Stream)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(SWFReader.FillStyleData)
    * SWFReader.eFillStyleType type
# SWFReader.SolidFillStyleData
  ## Members
    * Boolean Matches(SWFReader.FillStyleData)
    * Void Write(System.IO.Stream)
    * SWFReader.eFillStyleType get_type()
    * Void set_type(SWFReader.eFillStyleType)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(SWFReader.SolidFillStyleData)
    * SWFReader.eFillStyleType type
    * Byte red
    * Byte green
    * Byte blue
    * Byte alpha
# SWFReader.GradientRecord
  ## Members
    * Boolean Matches(SWFReader.GradientRecord)
    * Void Write(System.IO.Stream)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(Int32, Byte, Byte, Byte, Byte)
    * Void .ctor(SWFReader.GradientRecord)
    * Int32 ratio
    * Byte red
    * Byte green
    * Byte blue
    * Byte alpha
# SWFReader.eGradientType
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * SWFReader.eGradientType eLinear
    * SWFReader.eGradientType eRadial
# SWFReader.GradientFillStyleData
  ## Members
    * SWFReader.eGradientType get_gradType()
    * Void set_gradType(SWFReader.eGradientType)
    * SWFReader.Matrix33 get_transMat()
    * Void set_transMat(SWFReader.Matrix33)
    * System.Collections.Generic.List`1[SWFReader.GradientRecord] get_gradRecords()
    * Void set_gradRecords(System.Collections.Generic.List`1[SWFReader.GradientRecord])
    * Boolean Matches(SWFReader.FillStyleData)
    * Void AddRecord(Int32, Byte, Byte, Byte, Byte)
    * Void SortByRatio()
    * Void Write(System.IO.Stream)
    * SWFReader.eFillStyleType get_type()
    * Void set_type(SWFReader.eFillStyleType)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(SWFReader.GradientFillStyleData)
    * SWFReader.eGradientType gradType
    * SWFReader.Matrix33 transMat
    * System.Collections.Generic.List`1[SWFReader.GradientRecord] gradRecords
    * SWFReader.eFillStyleType type
# SWFReader.eBitmapFillType
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * SWFReader.eBitmapFillType eRepeat
    * SWFReader.eBitmapFillType eClamp
    * SWFReader.eBitmapFillType eRepeatPoint
    * SWFReader.eBitmapFillType eClampPoint
# SWFReader.BitmapFillStyleData
  ## Members
    * SWFReader.eBitmapFillType get_bitmapFillType()
    * Void set_bitmapFillType(SWFReader.eBitmapFillType)
    * Int32 get_charID()
    * Void set_charID(Int32)
    * SWFReader.Matrix33 get_transMat()
    * Void set_transMat(SWFReader.Matrix33)
    * Boolean Matches(SWFReader.FillStyleData)
    * Void Write(System.IO.Stream)
    * SWFReader.eFillStyleType get_type()
    * Void set_type(SWFReader.eFillStyleType)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(SWFReader.BitmapFillStyleData)
    * SWFReader.eBitmapFillType bitmapFillType
    * Int32 charID
    * SWFReader.Matrix33 transMat
    * SWFReader.eFillStyleType type
# SWFReader.FontKerningRecord
  ## Members
    * UInt16 get_leftChar()
    * Void set_leftChar(UInt16)
    * UInt16 get_rightChar()
    * Void set_rightChar(UInt16)
    * Int16 get_adjustment()
    * Void set_adjustment(Int16)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(SWFReader.FontKerningRecord)
    * Void .ctor(UInt16, UInt16, Int16)
    * UInt16 leftChar
    * UInt16 rightChar
    * Int16 adjustment
# SWFReader.Font
  ## Members
    * System.Collections.Generic.List`1[SWFReader.ShapeData] get_glyphs()
    * Void set_glyphs(System.Collections.Generic.List`1[SWFReader.ShapeData])
    * System.Collections.Generic.List`1[System.UInt16] get_glyphToCodeTable()
    * Void set_glyphToCodeTable(System.Collections.Generic.List`1[System.UInt16])
    * UInt16 get_ascent()
    * Void set_ascent(UInt16)
    * UInt16 get_descent()
    * Void set_descent(UInt16)
    * Int16 get_leading()
    * Void set_leading(Int16)
    * System.Collections.Generic.List`1[System.Int16] get_advanceTable()
    * Void set_advanceTable(System.Collections.Generic.List`1[System.Int16])
    * System.Collections.Generic.List`1[SWFReader.FontKerningRecord] get_kerningTable()
    * Void set_kerningTable(System.Collections.Generic.List`1[SWFReader.FontKerningRecord])
    * Int32 get_scaleFactor()
    * Void set_scaleFactor(Int32)
    * SWFReader.eDictionaryItemType get_type()
    * Void set_type(SWFReader.eDictionaryItemType)
    * Int32 get_Id()
    * Void set_Id(Int32)
    * Void Write(System.IO.Stream)
    * Void CalculateBounds(SWFReader.Matrix33, Int32 ByRef, Int32 ByRef, Int32 ByRef, Int32 ByRef)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(SWFReader.Font)
    * System.Collections.Generic.List`1[SWFReader.ShapeData] glyphs
    * System.Collections.Generic.List`1[System.UInt16] glyphToCodeTable
    * UInt16 ascent
    * UInt16 descent
    * Int16 leading
    * System.Collections.Generic.List`1[System.Int16] advanceTable
    * System.Collections.Generic.List`1[SWFReader.FontKerningRecord] kerningTable
    * Int32 scaleFactor
    * SWFReader.eDictionaryItemType type
    * Int32 Id
# SWFReader.LineCapStyle
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * SWFReader.LineCapStyle Round
    * SWFReader.LineCapStyle None
    * SWFReader.LineCapStyle Square
# SWFReader.LineJoinStyle
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * SWFReader.LineJoinStyle Round
    * SWFReader.LineJoinStyle Bevel
    * SWFReader.LineJoinStyle Miter
# SWFReader.LineStyleData
  ## Members
    * Boolean Matches(SWFReader.LineStyleData)
    * Void Write(System.IO.Stream)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(SWFReader.LineStyleData)
    * Byte red
    * Byte green
    * Byte blue
    * Byte alpha
    * Int32 width
    * SWFReader.LineCapStyle startcapstyle
    * SWFReader.LineCapStyle endcapstyle
    * SWFReader.LineJoinStyle joinstyle
    * Boolean noclose
    * Int32 FillStyle
    * Single miterlimitfactor
# SWFReader.Matrix33
  ## Members
    * Single[] get_values()
    * Void set_values(Single[])
    * Boolean Equals(SWFReader.Matrix33)
    * SWFReader.Matrix33 Mult(SWFReader.Matrix33, SWFReader.Matrix33)
    * Void Mult(SWFReader.Vec2, Int32 ByRef, Int32 ByRef)
    * Void MultNormalF(SWFReader.Vec2f, Single ByRef, Single ByRef)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(Single, Single, Single, Single, Single, Single, Single, Single, Single)
    * Void .ctor(SWFReader.Matrix33)
    * Single[] values
# SWFReader.Rect
  ## Members
    * Int32 get_minX()
    * Void set_minX(Int32)
    * Int32 get_maxX()
    * Void set_maxX(Int32)
    * Int32 get_minY()
    * Void set_minY(Int32)
    * Int32 get_maxY()
    * Void set_maxY(Int32)
    * Boolean Overlaps(SWFReader.Rect)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(Int32, Int32)
    * Void .ctor(Int32, Int32, Int32, Int32)
    * Void .ctor(SWFReader.Rect)
    * Int32 minX
    * Int32 maxX
    * Int32 minY
    * Int32 maxY
# SWFReader.Rectf
  ## Members
    * Single get_minX()
    * Void set_minX(Single)
    * Single get_maxX()
    * Void set_maxX(Single)
    * Single get_minY()
    * Void set_minY(Single)
    * Single get_maxY()
    * Void set_maxY(Single)
    * Boolean Overlaps(SWFReader.Rectf)
    * Boolean Equals(SWFReader.Rectf)
    * Boolean Contains(SWFReader.Rectf)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(Single, Single)
    * Void .ctor(Single, Single, Single, Single)
    * Void .ctor(SWFReader.Rectf)
    * Single minX
    * Single maxX
    * Single minY
    * Single maxY
# SWFReader.SubShape
  ## Members
    * System.Collections.Generic.List`1[SWFReader.Vec2] get_Points()
    * Void set_Points(System.Collections.Generic.List`1[SWFReader.Vec2])
    * System.Collections.Generic.List`1[SWFReader.Vec2] get_Lines()
    * Void set_Lines(System.Collections.Generic.List`1[SWFReader.Vec2])
    * System.Collections.Generic.List`1[System.Int32] get_Triangles()
    * Void set_Triangles(System.Collections.Generic.List`1[System.Int32])
    * System.Collections.Generic.List`1[SWFReader.Vec2] get_LinePoints()
    * Void set_LinePoints(System.Collections.Generic.List`1[SWFReader.Vec2])
    * System.Collections.Generic.List`1[System.Int32] get_LineTriangles()
    * Void set_LineTriangles(System.Collections.Generic.List`1[System.Int32])
    * System.Collections.Generic.List`1[SWFReader.Vec2] get_AAlines()
    * Void set_AAlines(System.Collections.Generic.List`1[SWFReader.Vec2])
    * System.Collections.Generic.List`1[SWFReader.Vec2f] get_AAvectors()
    * Void set_AAvectors(System.Collections.Generic.List`1[SWFReader.Vec2f])
    * System.Collections.Generic.List`1[SWFReader.Vec2] get_LineAAlines()
    * Void set_LineAAlines(System.Collections.Generic.List`1[SWFReader.Vec2])
    * System.Collections.Generic.List`1[SWFReader.Vec2f] get_LineAAvectors()
    * Void set_LineAAvectors(System.Collections.Generic.List`1[SWFReader.Vec2f])
    * Boolean get_IsClosed()
    * Void set_IsClosed(Boolean)
    * Boolean get_IsHole()
    * Void set_IsHole(Boolean)
    * Int32 get_FillStyle0()
    * Void set_FillStyle0(Int32)
    * Int32 get_FillStyle1()
    * Void set_FillStyle1(Int32)
    * Int32 get_LineStyle()
    * Void set_LineStyle(Int32)
    * Boolean Matches(SWFReader.SubShape)
    * Void Write(System.IO.Stream)
    * Void FlipVerts()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(SWFReader.SubShape)
    * System.Collections.Generic.List`1[SWFReader.Vec2] Points
    * System.Collections.Generic.List`1[SWFReader.Vec2] Lines
    * System.Collections.Generic.List`1[System.Int32] Triangles
    * System.Collections.Generic.List`1[SWFReader.Vec2] LinePoints
    * System.Collections.Generic.List`1[System.Int32] LineTriangles
    * System.Collections.Generic.List`1[SWFReader.Vec2] AAlines
    * System.Collections.Generic.List`1[SWFReader.Vec2f] AAvectors
    * System.Collections.Generic.List`1[SWFReader.Vec2] LineAAlines
    * System.Collections.Generic.List`1[SWFReader.Vec2f] LineAAvectors
    * Boolean IsClosed
    * Boolean IsHole
    * Int32 FillStyle0
    * Int32 FillStyle1
    * Int32 LineStyle
    * Boolean debughighlight
# SWFReader.StyleGroup
  ## Members
    * System.Collections.Generic.List`1[SWFReader.SubShape] get_SubShapes()
    * Void set_SubShapes(System.Collections.Generic.List`1[SWFReader.SubShape])
    * System.Collections.Generic.List`1[SWFReader.FillStyleData] get_FillStyles()
    * Void set_FillStyles(System.Collections.Generic.List`1[SWFReader.FillStyleData])
    * System.Collections.Generic.List`1[SWFReader.LineStyleData] get_LineStyles()
    * Void set_LineStyles(System.Collections.Generic.List`1[SWFReader.LineStyleData])
    * Boolean Matches(SWFReader.StyleGroup)
    * Void Write(System.IO.Stream)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(SWFReader.StyleGroup)
    * System.Collections.Generic.List`1[SWFReader.SubShape] SubShapes
    * System.Collections.Generic.List`1[SWFReader.FillStyleData] FillStyles
    * System.Collections.Generic.List`1[SWFReader.LineStyleData] LineStyles
# SWFReader.ShapeData
  ## Members
    * System.Collections.Generic.List`1[SWFReader.StyleGroup] get_StyleGroups()
    * Void set_StyleGroups(System.Collections.Generic.List`1[SWFReader.StyleGroup])
    * Int32 get_MinX()
    * Void set_MinX(Int32)
    * Int32 get_MaxX()
    * Void set_MaxX(Int32)
    * Int32 get_MinY()
    * Void set_MinY(Int32)
    * Int32 get_MaxY()
    * Void set_MaxY(Int32)
    * Boolean Matches(SWFReader.ShapeData)
    * Void Write(System.IO.Stream)
    * Int32 AddPoint(Int32, Int32)
    * Void AddLine(Int32, Int32)
    * Void StartStyleGroup(System.Collections.Generic.List`1[SWFReader.FillStyleData], System.Collections.Generic.List`1[SWFReader.LineStyleData])
    * Void StartSubShape(Int32, Int32, Int32)
    * Void FinaliseSubShape()
    * Void RemoveDegenerateEdges()
    * Void RemoveDummySubShapes()
    * Void CleanupSubShapes()
    * Void GenerateLines()
    * Void WeldDuplicateLineVerts()
    * Void GenerateAAinfo()
    * Void SplitSelfIntersectingShapes()
    * Void MergeSimilarSubShapes()
    * Void CollapseDuplicatedPoints()
    * Boolean FinaliseShape(Int32, Int32, Boolean)
    * Void Triangulate()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(SWFReader.ShapeData)
    * System.Collections.Generic.List`1[SWFReader.StyleGroup] StyleGroups
    * Int32 MinX
    * Int32 MaxX
    * Int32 MinY
    * Int32 MaxY
    * SWFReader.StyleGroup currGroup
    * SWFReader.SubShape currSubShape
    * System.Collections.Generic.List`1[SWFReader.Rectf] HDzones
    * SWFReader.Triangulator m_Triangulator
    * Boolean hack
# SWFReader.Shape
  ## Members
    * Boolean Matches(SWFReader.Shape)
    * Void Write(System.IO.Stream)
    * Void CalculateBounds(SWFReader.Matrix33, Int32 ByRef, Int32 ByRef, Int32 ByRef, Int32 ByRef)
    * SWFReader.eDictionaryItemType get_type()
    * Void set_type(SWFReader.eDictionaryItemType)
    * Int32 get_Id()
    * Void set_Id(Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(SWFReader.Shape)
    * SWFReader.eDictionaryItemType type
    * Int32 Id
    * SWFReader.ShapeData shapeData
# SWFReader.ShapeDrawer
  ## Members
    * Void DrawShapeStyleSubShape(SWFReader.ShapeData, SWFReader.StyleGroup, SWFReader.Matrix33, SWFReader.SubShape, System.Drawing.Graphics)
    * Void DrawSubShapeWithMatrix(SWFReader.ShapeData, SWFReader.SubShape, SWFReader.Matrix33, System.Drawing.Graphics, System.Drawing.Pen, System.Drawing.SolidBrush, System.Drawing.Pen, System.Drawing.SolidBrush)
    * Void DrawStyleGroupWithMatrix(SWFReader.ShapeData, SWFReader.StyleGroup, SWFReader.Matrix33, SWFReader.ColTransform, System.Drawing.Graphics)
    * Void DrawShapeWithMatrix(SWFReader.ShapeData, SWFReader.Matrix33, SWFReader.ColTransform, System.Drawing.Graphics)
    * Void DrawFrame(SWFReader.Sprite, SWFReader.Frame, System.Drawing.Graphics, SWFReader.Matrix33, SWFReader.ColTransform, System.Collections.Generic.List`1[SWFReader.DictionaryItem])
    * Void DrawTextField(SWFReader.TextField, System.Drawing.Graphics, SWFReader.Matrix33, SWFReader.ColTransform, System.Collections.Generic.List`1[SWFReader.DictionaryItem])
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
# SWFReader.Frame
  ## Members
    * System.String get_Name()
    * Void set_Name(System.String)
    * Int32 get_Start()
    * Void set_Start(Int32)
    * Int32 get_End()
    * Void set_End(Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String, Int32, Int32)
    * System.String Name
    * Int32 Start
    * Int32 End
# SWFReader.Sprite
  ## Members
    * SWFReader.eDictionaryItemType get_type()
    * Void set_type(SWFReader.eDictionaryItemType)
    * Int32 get_Id()
    * Void set_Id(Int32)
    * Void Write(System.IO.Stream)
    * Void CalculateBounds(SWFReader.Matrix33, Int32 ByRef, Int32 ByRef, Int32 ByRef, Int32 ByRef)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * SWFReader.eDictionaryItemType type
    * Int32 Id
    * SWFReader.DisplayList displayList
    * System.Collections.Generic.List`1[SWFReader.DLEntry] currentEntries
# SWFReader.StreamHelper
  ## Members
    * Int16 ReadShort(System.IO.Stream)
    * Int32 ReadInteger(System.IO.Stream)
    * Int64 ReadLong(System.IO.Stream)
    * Boolean ReadBoolean(System.IO.Stream)
    * System.String ReadString(System.IO.Stream)
    * System.Guid ReadGuid(System.IO.Stream)
    * System.IO.Stream ReadStreamE(System.IO.Stream)
    * Byte[] ReadStream(System.IO.Stream)
    * Single ReadSingle(System.IO.Stream)
    * Double ReadDouble(System.IO.Stream)
    * Void WriteInteger(System.IO.Stream, Int32)
    * Void WriteShort(System.IO.Stream, Int16)
    * Void WriteGUID(System.IO.Stream, System.Guid)
    * Void WriteLong(System.IO.Stream, Int64)
    * Void WriteBoolean(System.IO.Stream, Boolean)
    * Void WriteChunk(System.IO.Stream, System.String)
    * Int64 WriteChunkSize(System.IO.Stream)
    * Void PatchChunkSize(System.IO.Stream, Int64)
    * Void PatchOffset(System.IO.Stream, Int64)
    * Void WriteString(System.IO.Stream, System.String)
    * Void WriteDouble(System.IO.Stream, Double)
    * Void WriteSingle(System.IO.Stream, Single)
    * Void Align(System.IO.Stream, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
# SWFReader.eSWFUsageFlags
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * SWFReader.eSWFUsageFlags ActionScript
    * SWFReader.eSWFUsageFlags Video
    * SWFReader.eSWFUsageFlags Audio
    * SWFReader.eSWFUsageFlags MorphShapes
    * SWFReader.eSWFUsageFlags Filters
    * SWFReader.eSWFUsageFlags BlendModes
    * SWFReader.eSWFUsageFlags Buttons
    * SWFReader.eSWFUsageFlags NineSliceScaling
    * SWFReader.eSWFUsageFlags FocalRadialGradients
    * SWFReader.eSWFUsageFlags DeviceText
    * SWFReader.eSWFUsageFlags AssetImport
    * SWFReader.eSWFUsageFlags VersionTooHigh
    * SWFReader.eSWFUsageFlags CantPreview
    * SWFReader.eSWFUsageFlags MAX
# SWFReader.SwfFile
  ## Members
    * Void Trace(System.String)
    * Void Trace(System.String, System.Object[])
    * SWFReader.ShapeData BuildShapeData(System.Collections.Generic.List`1[SWFReader.SWFShapeRecord], SWFReader.SWFShape, Int32, Single, Int32)
    * Void GenerateGlyphLayout(SWFReader.TextField, Int32, Byte, Byte, Byte, Byte)
    * Int32 CountTags(System.Collections.Generic.List`1[SWFReader.SWFBaseTag])
    * Int32 ParseTags(SWFReader.Sprite, System.Collections.Generic.List`1[SWFReader.SWFBaseTag], Int32)
    * Void BuildYYSToStream(System.IO.Stream)
    * Byte[] GetSWFData(System.String, Boolean, Boolean, Int32, Int32, Int32, Int32, Int32, Int32, Boolean, Single)
    * Void Load(System.String, Boolean, Boolean, Boolean, Int32, Int32, Int32, Int32, Int32, Int32, Boolean, Single)
    * Void Save(System.String, Boolean, SWFReader.Rect)
    * Int32 GenerateImages(System.String, System.String, Int32, Int32, Single)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Byte[] JPEGtables
    * System.Collections.Generic.List`1[SWFReader.DictionaryItem] DictionaryItems
    * SWFReader.Sprite RootSprite
    * SWFReader.Timeline timeline
    * Int32 statusFlags
    * Int32 totalNumTags
    * System.String[] SWFUsageStrings
    * Single ShapeTolerance
    * Boolean BigEndian
    * Int32 FileVersion
    * Int32 SWF_EXT_FLAG
    * Single GlyphTolerance
# SWFReader.BitwiseBinaryReaderState
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Byte buff
    * Int32 currbit
    * Int64 pos
# SWFReader.BitwiseBinaryReader
  ## Members
    * Void Align()
    * Int32 ReadSInt(Int32)
    * UInt32 ReadUInt(Int32)
    * Single ReadFixed32()
    * Single ReadFixed32(Int32)
    * Single ReadFixed16()
    * Boolean ReadBooleanBit()
    * System.String ReadUTF8String()
    * Byte PeekByte()
    * UInt16 PeekUInt16()
    * UInt32 PeekUInt(Int32)
    * Void PushState()
    * Void PopState()
    * System.IO.Stream get_BaseStream()
    * Void Close()
    * Void Dispose()
    * Int32 PeekChar()
    * Int32 Read()
    * Boolean ReadBoolean()
    * Byte ReadByte()
    * SByte ReadSByte()
    * Char ReadChar()
    * Int16 ReadInt16()
    * UInt16 ReadUInt16()
    * Int32 ReadInt32()
    * UInt32 ReadUInt32()
    * Int64 ReadInt64()
    * UInt64 ReadUInt64()
    * Single ReadSingle()
    * Double ReadDouble()
    * System.Decimal ReadDecimal()
    * System.String ReadString()
    * Int32 Read(Char[], Int32, Int32)
    * Char[] ReadChars(Int32)
    * Int32 Read(Byte[], Int32, Int32)
    * Byte[] ReadBytes(Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.IO.Stream)
    * System.IO.Stream BaseStream
# SWFReader.SWFFileParser
  ## Members
    * Void ReadSWF(System.String)
    * Boolean ParseTags(SWFReader.BitwiseBinaryReader, System.Collections.Generic.List`1[SWFReader.SWFBaseTag])
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * SWFReader.SWFHeader header
    * System.Collections.Generic.List`1[SWFReader.SWFBaseTag] tagList
# SWFReader.SWFHeader
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Signature
    * Byte Version
    * UInt32 FileLength
    * SWFReader.SWFRect FrameSize
    * Single FrameRate
    * UInt16 FrameCount
    * Int32 MAX_VERSION
# SWFReader.LosslessFormat
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * SWFReader.LosslessFormat Unknown
    * SWFReader.LosslessFormat Lossless8bit
    * SWFReader.LosslessFormat Lossless15bit
    * SWFReader.LosslessFormat Lossless24bit
    * SWFReader.LosslessFormat Lossless32bit
# SWFReader.SWFBaseTag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.SWFDefineBitsTag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * UInt16 CharacterID
    * Byte[] JPEGData
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.SWFDefineBitsJPEG2Tag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * UInt16 CharacterID
    * Byte[] JPEGData
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.SWFDefineBitsJPEG3Tag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * UInt16 CharacterID
    * Byte[] ImageData
    * Byte[] BitmapAlphaData
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.SWFDefineBitsLosslessTag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * UInt16 CharacterID
    * Byte BitmapFormat
    * UInt16 BitmapWidth
    * UInt16 BitmapHeight
    * SWFReader.SWFColour[] ColourTable
    * Byte[] ColourPixelData
    * SWFReader.SWFColour[] BitmapPixelData
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.SWFDefineBitsLossless2Tag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * UInt16 CharacterID
    * Byte BitmapFormat
    * UInt16 BitmapWidth
    * UInt16 BitmapHeight
    * SWFReader.SWFColour[] ColourTable
    * Byte[] ColourPixelData
    * SWFReader.SWFColour[] BitmapPixelData
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.SWFDefineEditTextTag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * UInt16 CharacterID
    * SWFReader.SWFRect Bounds
    * Boolean HasText
    * Boolean WordWrap
    * Boolean Multiline
    * Boolean Password
    * Boolean ReadOnly
    * Boolean HasTextColour
    * Boolean HasMaxLength
    * Boolean HasFont
    * Boolean HasFontClass
    * Boolean AutoSize
    * Boolean HasLayout
    * Boolean NoSelect
    * Boolean Border
    * Boolean WasStatic
    * Boolean HTML
    * Boolean UseOutlines
    * UInt16 FontID
    * System.String FontClass
    * UInt16 FontHeight
    * SWFReader.SWFRGBA TextColour
    * UInt16 MaxLength
    * Byte Align
    * UInt16 LeftMargin
    * UInt16 RightMargin
    * UInt16 Indent
    * Int16 Leading
    * System.String VariableName
    * System.String InitialText
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.SWFDefineFontTag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * UInt16 FontID
    * UInt32[] OffsetTable
    * System.Collections.Generic.List`1[SWFReader.SWFShape] GlyphShapeTable
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.SWFDefineFont2Tag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Boolean HasLayout
    * Boolean ShiftJIS
    * Boolean SmallText
    * Boolean ANSI
    * Boolean WideOffsets
    * Boolean WideCodes
    * Boolean Italic
    * Boolean Bold
    * Byte LanguageCode
    * Byte NameLen
    * Byte[] Name
    * UInt16 NumGlyphs
    * UInt32 CodeTableOffset
    * UInt16[] CodeTable
    * UInt16 Ascent
    * UInt16 Descent
    * Int16 Leading
    * Int16[] AdvanceTable
    * System.Collections.Generic.List`1[SWFReader.SWFRect] BoundsTable
    * UInt16 KerningCount
    * System.Collections.Generic.List`1[SWFReader.SWFKerningRecord] KerningTable
    * UInt16 FontID
    * UInt32[] OffsetTable
    * System.Collections.Generic.List`1[SWFReader.SWFShape] GlyphShapeTable
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.SWFDefineFont3Tag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Boolean HasLayout
    * Boolean ShiftJIS
    * Boolean SmallText
    * Boolean ANSI
    * Boolean WideOffsets
    * Boolean WideCodes
    * Boolean Italic
    * Boolean Bold
    * Byte LanguageCode
    * Byte NameLen
    * Byte[] Name
    * UInt16 NumGlyphs
    * UInt32 CodeTableOffset
    * UInt16[] CodeTable
    * UInt16 Ascent
    * UInt16 Descent
    * Int16 Leading
    * Int16[] AdvanceTable
    * System.Collections.Generic.List`1[SWFReader.SWFRect] BoundsTable
    * UInt16 KerningCount
    * System.Collections.Generic.List`1[SWFReader.SWFKerningRecord] KerningTable
    * UInt16 FontID
    * UInt32[] OffsetTable
    * System.Collections.Generic.List`1[SWFReader.SWFShape] GlyphShapeTable
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.SWFDefineShapeTag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * UInt16 ShapeId
    * SWFReader.SWFRect ShapeBounds
    * SWFReader.SWFShapeWithStyle Shape
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.SWFDefineShape2Tag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * UInt16 ShapeId
    * SWFReader.SWFRect ShapeBounds
    * SWFReader.SWFShapeWithStyle Shape
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.SWFDefineShape3Tag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * UInt16 ShapeId
    * SWFReader.SWFRect ShapeBounds
    * SWFReader.SWFShapeWithStyle Shape
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.SWFDefineShape4Tag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * SWFReader.SWFRect EdgeBounds
    * Boolean UsesFillWindingRules
    * Boolean UsesNonScalingStrokes
    * Boolean UsesScalingStrokes
    * UInt16 ShapeId
    * SWFReader.SWFRect ShapeBounds
    * SWFReader.SWFShapeWithStyle Shape
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.SWFDefineSpriteTag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * UInt16 SpriteID
    * UInt16 FrameCount
    * System.Collections.Generic.List`1[SWFReader.SWFBaseTag] ControlTags
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.SWFDefineTextTag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * UInt16 CharacterID
    * SWFReader.SWFRect TextBounds
    * SWFReader.SWFMatrix TextMatrix
    * Byte GlyphBits
    * Byte AdvanceBits
    * System.Collections.Generic.List`1[SWFReader.SWFTextRecord] TextRecords
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.SWFDefineText2Tag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * UInt16 CharacterID
    * SWFReader.SWFRect TextBounds
    * SWFReader.SWFMatrix TextMatrix
    * Byte GlyphBits
    * Byte AdvanceBits
    * System.Collections.Generic.List`1[SWFReader.SWFTextRecord] TextRecords
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.SWFEndTag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.SWFFileAttributesTag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.SWFFrameLabelTag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.SWFJPEGTablesTag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Byte[] JPEGData
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.SWFPlaceObjectTag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * UInt16 CharacterId
    * UInt16 Depth
    * SWFReader.SWFMatrix Matrix
    * SWFReader.SWFColourTransform ColourTransform
    * Boolean HasCharacter
    * Boolean HasMatrix
    * Boolean HasColourTransform
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.SWFPlaceObject2Tag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Boolean HasClipActions
    * Boolean HasClipDepth
    * Boolean HasName
    * Boolean HasRatio
    * Boolean FlagMove
    * UInt16 Ratio
    * System.String Name
    * UInt16 ClipDepth
    * UInt16 CharacterId
    * UInt16 Depth
    * SWFReader.SWFMatrix Matrix
    * SWFReader.SWFColourTransform ColourTransform
    * Boolean HasCharacter
    * Boolean HasMatrix
    * Boolean HasColourTransform
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.SWFPlaceObject3Tag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Boolean HasClipActions
    * Boolean HasClipDepth
    * Boolean HasName
    * Boolean HasRatio
    * Boolean FlagMove
    * Boolean FlagOpaqueBackground
    * Boolean HasVisible
    * Boolean HasImage
    * Boolean HasClassName
    * Boolean HasCacheAsBitmap
    * Boolean HasBlendMode
    * Boolean HasFilterList
    * System.String ClassName
    * UInt16 Ratio
    * System.String Name
    * UInt16 ClipDepth
    * SWFReader.SWFFilterList SurfaceFilterList
    * Byte BlendMode
    * Byte BitmapCache
    * UInt16 CharacterId
    * UInt16 Depth
    * SWFReader.SWFMatrix Matrix
    * SWFReader.SWFColourTransform ColourTransform
    * Boolean HasCharacter
    * Boolean HasMatrix
    * Boolean HasColourTransform
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.TagType
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * SWFReader.TagType Unknown
    * SWFReader.TagType End
    * SWFReader.TagType ShowFrame
    * SWFReader.TagType DefineShape
    * SWFReader.TagType PlaceObject
    * SWFReader.TagType RemoveObject
    * SWFReader.TagType DefineBits
    * SWFReader.TagType DefineButton
    * SWFReader.TagType JPEGTables
    * SWFReader.TagType SetBackgroundColour
    * SWFReader.TagType DefineFont
    * SWFReader.TagType DefineText
    * SWFReader.TagType DoAction
    * SWFReader.TagType DefineSound
    * SWFReader.TagType StartSound
    * SWFReader.TagType DefineButtonSound
    * SWFReader.TagType SoundStreamHead
    * SWFReader.TagType SoundStreamBlock
    * SWFReader.TagType DefineBitsLossless
    * SWFReader.TagType DefineBitsJPEG2
    * SWFReader.TagType DefineShape2
    * SWFReader.TagType DefineButtonCxform
    * SWFReader.TagType PlaceObject2
    * SWFReader.TagType RemoveObject2
    * SWFReader.TagType DefineShape3
    * SWFReader.TagType DefineText2
    * SWFReader.TagType DefineButton2
    * SWFReader.TagType DefineBitsJPEG3
    * SWFReader.TagType DefineBitsLossless2
    * SWFReader.TagType DefineEditText
    * SWFReader.TagType DefineSprite
    * SWFReader.TagType FrameLabel
    * SWFReader.TagType SoundStreamHead2
    * SWFReader.TagType DefineMorphShape
    * SWFReader.TagType DefineFont2
    * SWFReader.TagType ImportAssets
    * SWFReader.TagType InitAction
    * SWFReader.TagType DefineVideoStream
    * SWFReader.TagType VideoFrame
    * SWFReader.TagType FileAttributes
    * SWFReader.TagType PlaceObject3
    * SWFReader.TagType ImportAssets2
    * SWFReader.TagType DefineFont3
    * SWFReader.TagType DefineScalingGrid
    * SWFReader.TagType DoABC
    * SWFReader.TagType DefineShape4
    * SWFReader.TagType DefineMorphShape2
    * SWFReader.TagType StartSound2
# SWFReader.SWFRemoveObjectTag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * UInt16 CharacterId
    * UInt16 Depth
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.SWFRemoveObject2Tag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * UInt16 Depth
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.SWFSetBackgroundColourTag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * SWFReader.SWFRGB BackgroundColour
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.SWFShowFrameTag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.SWFUnknownTag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Byte[] data
    * Int32 Type
    * UInt32 Size
    * Boolean LongTag
# SWFReader.SWFColour
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Byte red
    * Byte green
    * Byte blue
    * Byte alpha
# SWFReader.SWFRGB
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(Byte, Byte, Byte)
    * Byte red
    * Byte green
    * Byte blue
    * Byte alpha
# SWFReader.SWFRGBA
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(Byte, Byte, Byte, Byte)
    * Byte red
    * Byte green
    * Byte blue
    * Byte alpha
# SWFReader.SWFARGB
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(Byte, Byte, Byte, Byte)
    * Byte red
    * Byte green
    * Byte blue
    * Byte alpha
# SWFReader.SWFRGB15
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(Byte, Byte)
    * Byte red
    * Byte green
    * Byte blue
    * Byte alpha
# SWFReader.SWFColourTransform
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Boolean HasAddTerms
    * Boolean HasMultTerms
    * Int32 RedMult
    * Int32 GreenMult
    * Int32 BlueMult
    * Int32 RedAdd
    * Int32 GreenAdd
    * Int32 BlueAdd
# SWFReader.SWFColourTransformWithAlpha
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 AlphaMult
    * Int32 AlphaAdd
    * Boolean HasAddTerms
    * Boolean HasMultTerms
    * Int32 RedMult
    * Int32 GreenMult
    * Int32 BlueMult
    * Int32 RedAdd
    * Int32 GreenAdd
    * Int32 BlueAdd
# SWFReader.FillType
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * SWFReader.FillType Solid
    * SWFReader.FillType LinearGradient
    * SWFReader.FillType RadialGradient
    * SWFReader.FillType FocalRadialGradient
    * SWFReader.FillType RepeatingBitmap
    * SWFReader.FillType ClippedBitmap
    * SWFReader.FillType NonSmoothedRepeatingBitmap
    * SWFReader.FillType NonSmoothedClippedBitmap
# SWFReader.SWFFillStyle
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Byte Type
    * SWFReader.SWFRGB Colour
    * SWFReader.SWFMatrix GradientMatrix
    * SWFReader.SWFGradient GradientData
    * UInt16 BitmapId
    * SWFReader.SWFMatrix BitmapMatrix
# SWFReader.SWFGradRecord
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Byte Ratio
    * SWFReader.SWFColour Colour
# SWFReader.GradientSpreadMode
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * SWFReader.GradientSpreadMode Pad
    * SWFReader.GradientSpreadMode Reflect
    * SWFReader.GradientSpreadMode Repeat
    * SWFReader.GradientSpreadMode Reserved
# SWFReader.GradientInterpolationMode
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * SWFReader.GradientInterpolationMode NormalRGB
    * SWFReader.GradientInterpolationMode LinearRGB
    * SWFReader.GradientInterpolationMode Reserved1
    * SWFReader.GradientInterpolationMode Reserved2
# SWFReader.SWFGradient
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Byte SpreadMode
    * Byte InterpolationMode
    * Byte NumGradients
    * System.Collections.Generic.List`1[SWFReader.SWFGradRecord] GradientRecords
    * UInt16 FocalPoint
# SWFReader.SWFFillStyleArray
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.List`1[SWFReader.SWFFillStyle] FillStyles
# SWFReader.FilterType
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * SWFReader.FilterType DropShadow
    * SWFReader.FilterType Blur
    * SWFReader.FilterType Glow
    * SWFReader.FilterType Bevel
    * SWFReader.FilterType GradientGlow
    * SWFReader.FilterType Convolution
    * SWFReader.FilterType ColourMatrix
    * SWFReader.FilterType GradientBevel
# SWFReader.SWFFilterList
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.List`1[SWFReader.SWFFilter] Filters
# SWFReader.SWFFilter
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Byte FilterID
# SWFReader.SWFDropShadowFilter
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * SWFReader.SWFRGBA DropShadowColour
    * Single BlurX
    * Single BlurY
    * Single Angle
    * Single Distance
    * Single Strength
    * Boolean InnerShadow
    * Boolean Knockout
    * Boolean CompositeSource
    * UInt32 Passes
    * Byte FilterID
# SWFReader.SWFBlurFilter
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Single BlurX
    * Single BlurY
    * UInt32 Passes
    * Byte FilterID
# SWFReader.SWFGlowFilter
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * SWFReader.SWFRGBA GlowColour
    * Single BlurX
    * Single BlurY
    * Single Strength
    * Boolean InnerGlow
    * Boolean Knockout
    * Boolean CompositeSource
    * UInt32 Passes
    * Byte FilterID
# SWFReader.SWFBevelFilter
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * SWFReader.SWFRGBA ShadowColour
    * SWFReader.SWFRGBA HighlightColour
    * Single BlurX
    * Single BlurY
    * Single Angle
    * Single Distance
    * Single Strength
    * Boolean InnerShadow
    * Boolean Knockout
    * Boolean CompositeSource
    * Boolean OnTop
    * UInt32 Passes
    * Byte FilterID
# SWFReader.SWFGradientGlowFilter
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.List`1[SWFReader.SWFRGBA] GradientColours
    * Byte[] GradientRatios
    * Single BlurX
    * Single BlurY
    * Single Angle
    * Single Distance
    * Single Strength
    * Boolean InnerGlow
    * Boolean Knockout
    * Boolean CompositeSource
    * Boolean OnTop
    * UInt32 Passes
    * Byte FilterID
# SWFReader.SWFConvolutionFilter
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Byte MatrixX
    * Byte MatrixY
    * Single Divisor
    * Single Bias
    * Single[] Matrix
    * SWFReader.SWFRGBA DefaultColour
    * Boolean Clamp
    * Boolean PreserveAlpha
    * Byte FilterID
# SWFReader.SWFColourMatrixFilter
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Single[] Matrix
    * Byte FilterID
# SWFReader.SWFGradientBevelFilter
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.List`1[SWFReader.SWFRGBA] GradientColours
    * Byte[] GradientRatios
    * Single BlurX
    * Single BlurY
    * Single Angle
    * Single Distance
    * Single Strength
    * Boolean InnerShadow
    * Boolean Knockout
    * Boolean CompositeSource
    * Boolean OnTop
    * UInt32 Passes
    * Byte FilterID
# SWFReader.SWFKerningRecord
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader, Boolean)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * UInt16 KerningCode1
    * UInt16 KerningCode2
    * Int16 KerningAdjustment
# SWFReader.SWFLineCapStyle
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * SWFReader.SWFLineCapStyle Round
    * SWFReader.SWFLineCapStyle None
    * SWFReader.SWFLineCapStyle Square
# SWFReader.SWFLineJoinStyle
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * SWFReader.SWFLineJoinStyle Round
    * SWFReader.SWFLineJoinStyle Bevel
    * SWFReader.SWFLineJoinStyle Miter
# SWFReader.SWFLineStyle
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * UInt16 Width
    * SWFReader.SWFColour Colour
    * Byte StartCapStyle
    * Byte JoinStyle
    * Boolean HasFill
    * Boolean NoHScale
    * Boolean NoVScale
    * Boolean PixelHinting
    * Boolean NoClose
    * Byte EndCapStyle
    * UInt16 MiterLimitFactor
    * SWFReader.SWFFillStyle Fill
# SWFReader.SWFLineStyleArray
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.List`1[SWFReader.SWFLineStyle] LineStyles
# SWFReader.SWFMatrix
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Single[,] elements
# SWFReader.SWFRect
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * Int32 Width()
    * Int32 Height()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 Xmin
    * Int32 Xmax
    * Int32 Ymin
    * Int32 Ymax
# SWFReader.SWFShape
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.List`1[SWFReader.SWFShapeRecord] ShapeRecords
# SWFReader.SWFShapeWithStyle
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * SWFReader.SWFFillStyleArray FillStyles
    * SWFReader.SWFLineStyleArray LineStyles
    * System.Collections.Generic.List`1[SWFReader.SWFShapeRecord] ShapeRecords
# SWFReader.SWFShapeRecord
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader, Int32, UInt32 ByRef, UInt32 ByRef)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Boolean IsEdgeRecord
# SWFReader.SWFEndShapeRecord
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader, Int32, UInt32 ByRef, UInt32 ByRef)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Boolean IsEdgeRecord
# SWFReader.SWFStyleChangeRecord
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader, Int32, UInt32 ByRef, UInt32 ByRef)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Boolean NewStyles
    * Boolean LineStyleChange
    * Boolean FillStyle1Change
    * Boolean FillStyle0Change
    * Boolean MoveTo
    * Int32 MoveDeltaX
    * Int32 MoveDeltaY
    * UInt32 FillStyle0
    * UInt32 FillStyle1
    * UInt32 LineStyle
    * SWFReader.SWFFillStyleArray FillStyles
    * SWFReader.SWFLineStyleArray LineStyles
    * Boolean IsEdgeRecord
# SWFReader.SWFStraightEdgeRecord
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader, Int32, UInt32 ByRef, UInt32 ByRef)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 DeltaX
    * Int32 DeltaY
    * Boolean IsEdgeRecord
# SWFReader.SWFCurvedEdgeRecord
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader, Int32, UInt32 ByRef, UInt32 ByRef)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 ControlDeltaX
    * Int32 ControlDeltaY
    * Int32 AnchorDeltaX
    * Int32 AnchorDeltaY
    * Boolean IsEdgeRecord
# SWFReader.SWFTextRecord
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * UInt32 TextRecordType
    * Boolean HasFont
    * Boolean HasColour
    * Boolean HasYOffset
    * Boolean HasXOffset
    * UInt16 FontID
    * SWFReader.SWFColour TextColour
    * Int16 XOffset
    * Int16 YOffset
    * UInt16 TextHeight
    * System.Collections.Generic.List`1[SWFReader.SWFGlyphEntry] GlyphEntries
# SWFReader.SWFGlyphEntry
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * UInt32 GlyphIndex
    * Int32 GlyphAdvance
# SWFReader.eAlignment
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * Int32 value__
    * SWFReader.eAlignment eLeft
    * SWFReader.eAlignment eRight
    * SWFReader.eAlignment eCenter
    * SWFReader.eAlignment eJustify
# SWFReader.TextGlyphEntry
  ## Members
    * Int32 get_glyphIndex()
    * Void set_glyphIndex(Int32)
    * SWFReader.Matrix33 get_transMat()
    * Void set_transMat(SWFReader.Matrix33)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(SWFReader.TextGlyphEntry)
    * Int32 glyphIndex
    * SWFReader.Matrix33 transMat
# SWFReader.TextStyleEntry
  ## Members
    * Int32 get_fontID()
    * Void set_fontID(Int32)
    * Byte get_red()
    * Void set_red(Byte)
    * Byte get_green()
    * Void set_green(Byte)
    * Byte get_blue()
    * Void set_blue(Byte)
    * Byte get_alpha()
    * Void set_alpha(Byte)
    * System.Collections.Generic.List`1[SWFReader.TextGlyphEntry] get_glyphEntries()
    * Void set_glyphEntries(System.Collections.Generic.List`1[SWFReader.TextGlyphEntry])
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(SWFReader.TextStyleEntry)
    * Int32 fontID
    * Byte red
    * Byte green
    * Byte blue
    * Byte alpha
    * System.Collections.Generic.List`1[SWFReader.TextGlyphEntry] glyphEntries
# SWFReader.TextField
  ## Members
    * Int32 get_MinX()
    * Void set_MinX(Int32)
    * Int32 get_MaxX()
    * Void set_MaxX(Int32)
    * Int32 get_MinY()
    * Void set_MinY(Int32)
    * Int32 get_MaxY()
    * Void set_MaxY(Int32)
    * Boolean get_wordWrap()
    * Void set_wordWrap(Boolean)
    * Boolean get_multiline()
    * Void set_multiline(Boolean)
    * Boolean get_border()
    * Void set_border(Boolean)
    * Int32 get_fontHeight()
    * Void set_fontHeight(Int32)
    * Int32 get_maxLength()
    * Void set_maxLength(Int32)
    * SWFReader.eAlignment get_alignment()
    * Void set_alignment(SWFReader.eAlignment)
    * Int32 get_leftMargin()
    * Void set_leftMargin(Int32)
    * Int32 get_rightMargin()
    * Void set_rightMargin(Int32)
    * Int32 get_indent()
    * Void set_indent(Int32)
    * Int32 get_leading()
    * Void set_leading(Int32)
    * System.String get_text()
    * Void set_text(System.String)
    * System.Collections.Generic.List`1[SWFReader.TextStyleEntry] get_styleEntries()
    * Void set_styleEntries(System.Collections.Generic.List`1[SWFReader.TextStyleEntry])
    * SWFReader.eDictionaryItemType get_type()
    * Void set_type(SWFReader.eDictionaryItemType)
    * Int32 get_Id()
    * Void set_Id(Int32)
    * Void Write(System.IO.Stream)
    * Void CalculateBounds(SWFReader.Matrix33, Int32 ByRef, Int32 ByRef, Int32 ByRef, Int32 ByRef)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(SWFReader.TextField)
    * Int32 MinX
    * Int32 MaxX
    * Int32 MinY
    * Int32 MaxY
    * Boolean wordWrap
    * Boolean multiline
    * Boolean border
    * Int32 fontHeight
    * Int32 maxLength
    * SWFReader.eAlignment alignment
    * Int32 leftMargin
    * Int32 rightMargin
    * Int32 indent
    * Int32 leading
    * System.String text
    * System.Collections.Generic.List`1[SWFReader.TextStyleEntry] styleEntries
    * SWFReader.eDictionaryItemType type
    * Int32 Id
# SWFReader.TimelineObject
  ## Members
    * Int32 get_CharID()
    * Void set_CharID(Int32)
    * Int32 get_CharIndex()
    * Void set_CharIndex(Int32)
    * Int32 get_Depth()
    * Void set_Depth(Int32)
    * Int32 get_ClipDepth()
    * Void set_ClipDepth(Int32)
    * SWFReader.Matrix33 get_transMat()
    * Void set_transMat(SWFReader.Matrix33)
    * SWFReader.ColTransform get_colTrans()
    * Void set_colTrans(SWFReader.ColTransform)
    * Int32 get_MinX()
    * Void set_MinX(Int32)
    * Int32 get_MaxX()
    * Void set_MaxX(Int32)
    * Int32 get_MinY()
    * Void set_MinY(Int32)
    * Int32 get_MaxY()
    * Void set_MaxY(Int32)
    * Void Write(System.IO.Stream)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(SWFReader.TimelineObject)
    * Int32 CharID
    * Int32 CharIndex
    * Int32 Depth
    * Int32 ClipDepth
    * SWFReader.Matrix33 transMat
    * SWFReader.ColTransform colTrans
    * Int32 MinX
    * Int32 MaxX
    * Int32 MinY
    * Int32 MaxY
# SWFReader.TimelineFrame
  ## Members
    * System.Collections.Generic.List`1[SWFReader.TimelineObject] get_Objects()
    * Void set_Objects(System.Collections.Generic.List`1[SWFReader.TimelineObject])
    * Int32 get_MinX()
    * Void set_MinX(Int32)
    * Int32 get_MaxX()
    * Void set_MaxX(Int32)
    * Int32 get_MinY()
    * Void set_MinY(Int32)
    * Int32 get_MaxY()
    * Void set_MaxY(Int32)
    * Void Write(System.IO.Stream)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.List`1[SWFReader.TimelineObject] Objects
    * Int32 MinX
    * Int32 MaxX
    * Int32 MinY
    * Int32 MaxY
# SWFReader.SpriteDescription
  ## Members
    * System.Collections.Generic.List`1[SWFReader.TimelineObject] get_objList()
    * Void set_objList(System.Collections.Generic.List`1[SWFReader.TimelineObject])
    * Int32 get_minX()
    * Void set_minX(Int32)
    * Int32 get_maxX()
    * Void set_maxX(Int32)
    * Int32 get_minY()
    * Void set_minY(Int32)
    * Int32 get_maxY()
    * Void set_maxY(Int32)
    * Int32 get_largestDepth()
    * Void set_largestDepth(Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.List`1[SWFReader.TimelineObject] objList
    * Int32 minX
    * Int32 maxX
    * Int32 minY
    * Int32 maxY
    * Int32 largestDepth
# SWFReader.Timeline
  ## Members
    * System.Collections.Generic.List`1[SWFReader.DictionaryItem] get_UsedItems()
    * Void set_UsedItems(System.Collections.Generic.List`1[SWFReader.DictionaryItem])
    * System.Collections.Generic.List`1[SWFReader.TimelineFrame] get_Frames()
    * Void set_Frames(System.Collections.Generic.List`1[SWFReader.TimelineFrame])
    * Int32 get_FrameRate()
    * Void set_FrameRate(Int32)
    * Int32 get_MinX()
    * Void set_MinX(Int32)
    * Int32 get_MaxX()
    * Void set_MaxX(Int32)
    * Int32 get_MinY()
    * Void set_MinY(Int32)
    * Int32 get_MaxY()
    * Void set_MaxY(Int32)
    * Int32 get_MaskWidth()
    * Void set_MaskWidth(Int32)
    * Int32 get_MaskHeight()
    * Void set_MaskHeight(Int32)
    * System.Collections.Generic.List`1[SWFReader.CollisionMask] get_Masks()
    * Void set_Masks(System.Collections.Generic.List`1[SWFReader.CollisionMask])
    * Void Write(System.IO.Stream)
    * Void Build(SWFReader.Sprite, System.Collections.Generic.List`1[SWFReader.DictionaryItem], Boolean, SWFReader.Rect, Int32, Int32, Int32, Int32, Int32, Int32, Boolean)
    * SWFReader.SpriteDescription BuildFromSprite(SWFReader.Sprite, System.Collections.Generic.List`1[SWFReader.DictionaryItem], SWFReader.Matrix33, SWFReader.ColTransform, Boolean, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.List`1[SWFReader.DictionaryItem] UsedItems
    * System.Collections.Generic.List`1[SWFReader.TimelineFrame] Frames
    * Int32 FrameRate
    * Int32 MinX
    * Int32 MaxX
    * Int32 MinY
    * Int32 MaxY
    * Int32 MaskWidth
    * Int32 MaskHeight
    * System.Collections.Generic.List`1[SWFReader.CollisionMask] Masks
    * Single g_TwipScale
# SWFReader.Triangulator
  ## Members
    * Single Area(System.Collections.Generic.List`1[SWFReader.Vec2])
    * Int64 AreaX2(System.Collections.Generic.List`1[SWFReader.Vec2])
    * Boolean InsideTriangle(Single, Single, Single, Single, Single, Single, Single, Single)
    * Boolean Process(System.Collections.Generic.List`1[SWFReader.Vec2], System.Collections.Generic.List`1[System.Int32], Boolean)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Single EPSILON
# SWFReader.Vec2
  ## Members
    * Int32 get_X()
    * Void set_X(Int32)
    * Int32 get_Y()
    * Void set_Y(Int32)
    * Boolean Equals(SWFReader.Vec2)
    * Int64 SqDist(SWFReader.Vec2)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(Int32, Int32)
    * Void .ctor(Single, Single)
    * Void .ctor(SWFReader.Vec2)
    * Int32 X
    * Int32 Y
# GMAssetCompiler.Trace
  ## Members
    * System.String get_Filename()
    * Void set_Filename(System.String)
    * Void Write(System.String)
    * Void Write(System.String, System.Object[])
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Filename
    * System.IO.FileStream _storageFileStream
    * System.IO.StreamWriter _streamWriter
# GMAssetCompiler.WinTrustDataUIChoice
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * UInt32 value__
    * GMAssetCompiler.WinTrustDataUIChoice All
    * GMAssetCompiler.WinTrustDataUIChoice None
    * GMAssetCompiler.WinTrustDataUIChoice NoBad
    * GMAssetCompiler.WinTrustDataUIChoice NoGood
# GMAssetCompiler.WinTrustDataRevocationChecks
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * UInt32 value__
    * GMAssetCompiler.WinTrustDataRevocationChecks None
    * GMAssetCompiler.WinTrustDataRevocationChecks WholeChain
# GMAssetCompiler.WinTrustDataChoice
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * UInt32 value__
    * GMAssetCompiler.WinTrustDataChoice File
    * GMAssetCompiler.WinTrustDataChoice Catalog
    * GMAssetCompiler.WinTrustDataChoice Blob
    * GMAssetCompiler.WinTrustDataChoice Signer
    * GMAssetCompiler.WinTrustDataChoice Certificate
# GMAssetCompiler.WinTrustDataStateAction
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * UInt32 value__
    * GMAssetCompiler.WinTrustDataStateAction Ignore
    * GMAssetCompiler.WinTrustDataStateAction Verify
    * GMAssetCompiler.WinTrustDataStateAction Close
    * GMAssetCompiler.WinTrustDataStateAction AutoCache
    * GMAssetCompiler.WinTrustDataStateAction AutoCacheFlush
# GMAssetCompiler.WinTrustDataProvFlags
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * UInt32 value__
    * GMAssetCompiler.WinTrustDataProvFlags UseIe4TrustFlag
    * GMAssetCompiler.WinTrustDataProvFlags NoIe4ChainFlag
    * GMAssetCompiler.WinTrustDataProvFlags NoPolicyUsageFlag
    * GMAssetCompiler.WinTrustDataProvFlags RevocationCheckNone
    * GMAssetCompiler.WinTrustDataProvFlags RevocationCheckEndCert
    * GMAssetCompiler.WinTrustDataProvFlags RevocationCheckChain
    * GMAssetCompiler.WinTrustDataProvFlags RevocationCheckChainExcludeRoot
    * GMAssetCompiler.WinTrustDataProvFlags SaferFlag
    * GMAssetCompiler.WinTrustDataProvFlags HashOnlyFlag
    * GMAssetCompiler.WinTrustDataProvFlags UseDefaultOsverCheck
    * GMAssetCompiler.WinTrustDataProvFlags LifetimeSigningFlag
    * GMAssetCompiler.WinTrustDataProvFlags CacheOnlyUrlRetrieval
    * GMAssetCompiler.WinTrustDataProvFlags DisableMD2andMD4
# GMAssetCompiler.WinTrustDataUIContext
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * UInt32 value__
    * GMAssetCompiler.WinTrustDataUIContext Execute
    * GMAssetCompiler.WinTrustDataUIContext Install
# GMAssetCompiler.WinTrustFileInfo
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String)
# GMAssetCompiler.WinTrustData
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String)
# GMAssetCompiler.WinVerifyTrustResult
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.String ToString(System.String, System.IFormatProvider)
    * Int32 CompareTo(System.Object)
    * System.String ToString(System.String)
    * System.String ToString(System.IFormatProvider)
    * Boolean HasFlag(System.Enum)
    * System.TypeCode GetTypeCode()
    * System.Type GetType()
    * UInt32 value__
    * GMAssetCompiler.WinVerifyTrustResult Success
    * GMAssetCompiler.WinVerifyTrustResult ProviderUnknown
    * GMAssetCompiler.WinVerifyTrustResult ActionUnknown
    * GMAssetCompiler.WinVerifyTrustResult SubjectFormUnknown
    * GMAssetCompiler.WinVerifyTrustResult SubjectNotTrusted
    * GMAssetCompiler.WinVerifyTrustResult FileNotSigned
    * GMAssetCompiler.WinVerifyTrustResult SubjectExplicitlyDistrusted
    * GMAssetCompiler.WinVerifyTrustResult SignatureOrFileCorrupt
    * GMAssetCompiler.WinVerifyTrustResult SubjectCertExpired
    * GMAssetCompiler.WinVerifyTrustResult SubjectCertificateRevoked
# GMAssetCompiler.WinTrust
  ## Members
    * Boolean VerifyEmbeddedSignature(System.String)
    * Boolean VerifySecurity(System.String, System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
# <PrivateImplementationDetails>{4184FEE6-43B8-4B01-9762-CC6ADB80E913}
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
# GMAssetCompiler.GMShader+<>c__DisplayClass6
  ## Members
    * Void <ExecuteCMDWithResult>b__4(System.Object, System.Diagnostics.DataReceivedEventArgs)
    * Void <ExecuteCMDWithResult>b__5(System.Object, System.Diagnostics.DataReceivedEventArgs)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String tempstring
# GMAssetCompiler.GMObject+<>c__DisplayClass1
  ## Members
    * Boolean <UpdateEventCode>b__0(System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String filename
# GMAssetCompiler.GMRoom+<>c__DisplayClass2
  ## Members
    * Boolean <UpdateCreationCode>b__0(System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMInstance])
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 id
# GMAssetCompiler.GMSound+<>c__DisplayClass5
  ## Members
    * Void <DoFFProbe>b__1(System.Object, System.Diagnostics.DataReceivedEventArgs)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String output
# GMAssetCompiler.GMTimeLine+<>c__DisplayClass1
  ## Members
    * Boolean <UpdateEventCode>b__0(System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String filename
# GMAssetCompiler.Loader+<ParseGMLFile>d__0
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(Int32)
    * System.String[] _gml
    * System.String[] <>3___gml
    * System.Text.StringBuilder <sb>5__1
    * System.String <name>5__2
    * System.String <s>5__3
    * System.String <st>5__4
    * System.String[] <p>5__5
    * System.String[] <>7__wrap7
    * Int32 <>7__wrap8
# NDesk.Options.OptionSet+<>c__DisplayClass3
  ## Members
    * Void <Add>b__2(NDesk.Options.OptionValueCollection)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Action`1[System.String] action
# NDesk.Options.OptionSet+<>c__DisplayClass6
  ## Members
    * Void <Add>b__5(NDesk.Options.OptionValueCollection)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * NDesk.Options.OptionAction`2[System.String,System.String] action
# <PrivateImplementationDetails>{4184FEE6-43B8-4B01-9762-CC6ADB80E913}+__StaticArrayInitTypeSize=24
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
# <PrivateImplementationDetails>{4184FEE6-43B8-4B01-9762-CC6ADB80E913}+__StaticArrayInitTypeSize=20
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
# <PrivateImplementationDetails>{4184FEE6-43B8-4B01-9762-CC6ADB80E913}+__StaticArrayInitTypeSize=18
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
# <PrivateImplementationDetails>{4184FEE6-43B8-4B01-9762-CC6ADB80E913}+__StaticArrayInitTypeSize=50
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
# GMAssetCompiler.GML2VM+<>c__DisplayClass1
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.List`1[System.String] strings
# GMAssetCompiler.GML2VM+<>c__DisplayClass3
  ## Members
    * Boolean <CompileJS>b__0(System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c__DisplayClass1 CS$<>8__locals2
    * GMAssetCompiler.YYJSPatchEntry patch
# GMAssetCompiler.HTML5Saver+<>c__DisplayClass9
  ## Members
    * Void <WriteAudioGroups>b__8(System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMAudioGroup], System.IO.TextWriter, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.TextWriter _s
# GMAssetCompiler.HTML5Saver+<>c__DisplayClassc
  ## Members
    * Void <WriteSounds>b__b(System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMSound], System.IO.TextWriter, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.TextWriter _s
# GMAssetCompiler.HTML5Saver+<>c__DisplayClass13
  ## Members
    * Void <WriteBackgrounds>b__12(System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMBackground], System.IO.TextWriter, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMRoom]] _rooms
    * System.IO.TextWriter _s
# GMAssetCompiler.HTML5Saver+<>c__DisplayClass16
  ## Members
    * Void <WritePaths>b__15(System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMPath], System.IO.TextWriter, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.TextWriter _s
# GMAssetCompiler.HTML5Saver+<>c__DisplayClass19
  ## Members
    * Void <WriteScripts>b__18(System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMScript], System.IO.TextWriter, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.TextWriter _s
# GMAssetCompiler.HTML5Saver+<>c__DisplayClass1c
  ## Members
    * Void <WriteScriptNames>b__1b(System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMScript], System.IO.TextWriter, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.TextWriter _s
# GMAssetCompiler.HTML5Saver+<>c__DisplayClass1f
  ## Members
    * Void <WriteShaders>b__1e(System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMShader], System.IO.TextWriter, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.TextWriter _s
# GMAssetCompiler.HTML5Saver+<>c__DisplayClass22
  ## Members
    * Void <WriteFonts>b__21(System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMFont], System.IO.TextWriter, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.TextWriter _s
# GMAssetCompiler.HTML5Saver+<>c__DisplayClass25
  ## Members
    * Void <WriteGMEvent>b__24(GMAssetCompiler.GMAction, System.IO.TextWriter, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String _basename
# GMAssetCompiler.HTML5Saver+<>c__DisplayClass28
  ## Members
    * Void <WriteTimelines>b__27(System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMTimeLine], System.IO.TextWriter, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.TextWriter _s
# GMAssetCompiler.HTML5Saver+<>c__DisplayClass31
  ## Members
    * Void <WriteObjects>b__2a(System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMObject], System.IO.TextWriter, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.TextWriter _s
# GMAssetCompiler.HTML5Saver+<>c__DisplayClass31+<>c__DisplayClass33
  ## Members
    * Void <WriteObjects>b__2b(System.Collections.Generic.IList`1[GMAssetCompiler.SubTypeAndEvent], System.IO.TextWriter, Int32)
    * Void <WriteObjects>b__2d(System.Collections.Generic.IList`1[GMAssetCompiler.SubTypeAndEvent], System.IO.TextWriter, Int32)
    * Void <WriteObjects>b__2f(System.Collections.Generic.IList`1[GMAssetCompiler.SubTypeAndEvent], System.IO.TextWriter, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c__DisplayClass31 CS$<>8__locals32
    * System.String basename
    * Int32 count
    * System.IO.TextWriter __s
# GMAssetCompiler.HTML5Saver+<>c__DisplayClass31+<>c__DisplayClass33+<>c__DisplayClass35
  ## Members
    * Void <WriteObjects>b__2c(GMAssetCompiler.SubTypeAndEvent, System.IO.TextWriter, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c__DisplayClass33 CS$<>8__locals34
    * <>c__DisplayClass31 CS$<>8__locals32
    * Int32 _nEvent
# GMAssetCompiler.HTML5Saver+<>c__DisplayClass31+<>c__DisplayClass33+<>c__DisplayClass37
  ## Members
    * Void <WriteObjects>b__2e(GMAssetCompiler.SubTypeAndEvent, System.IO.TextWriter, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c__DisplayClass33 CS$<>8__locals34
    * <>c__DisplayClass31 CS$<>8__locals32
    * Int32 _nEvent
# GMAssetCompiler.HTML5Saver+<>c__DisplayClass31+<>c__DisplayClass33+<>c__DisplayClass39
  ## Members
    * Void <WriteObjects>b__30(GMAssetCompiler.SubTypeAndEvent, System.IO.TextWriter, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c__DisplayClass33 CS$<>8__locals34
    * <>c__DisplayClass31 CS$<>8__locals32
    * Int32 _nEvent
# GMAssetCompiler.HTML5Saver+<>c__DisplayClass3c
  ## Members
    * Void <WriteRooms>b__3b(System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMRoom], System.IO.TextWriter, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.TextWriter _s
# GMAssetCompiler.HTML5Saver+<>c__DisplayClass44
  ## Members
    * Void <WriteTexturePages>b__41(GMAssetCompiler.TexturePageEntry, System.IO.TextWriter, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.TextWriter _s
# GMAssetCompiler.Output.LLVM_Android+<>c__DisplayClass1
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.List`1[System.Diagnostics.Process] results
    * GMAssetCompiler.Output.LLVM_Android <>4__this
    * System.String arch
# GMAssetCompiler.Output.LLVM_Android+<>c__DisplayClass3
  ## Members
    * Void <ClangCompile>b__0(System.Object)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c__DisplayClass1 CS$<>8__locals2
    * System.String objDir
    * System.String responseFileName
# GMAssetCompiler.Output.LLVM_Windows+<>c__DisplayClass4
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.List`1[System.Diagnostics.Process] results
    * GMAssetCompiler.Output.LLVM_Windows <>4__this
# GMAssetCompiler.Output.LLVM_Windows+<>c__DisplayClass6
  ## Members
    * Void <ClangCompile>b__1(System.Object)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c__DisplayClass4 CS$<>8__locals5
    * System.String objDir
    * System.String responseFileName
# <PrivateImplementationDetails>{4184FEE6-43B8-4B01-9762-CC6ADB80E913}+__StaticArrayInitTypeSize=16
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
# GMAssetCompiler.WADSaver`1+<>c__DisplayClass5[TCode]
  ## Members
    * Void <WriteSounds>b__3(System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMSound], System.IO.Stream, GMAssetCompiler.IFF, Int64)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * GMAssetCompiler.WADSaver`1[TCode] <>4__this
    * GMAssetCompiler.IFF _iff
# GMAssetCompiler.WADSaver`1+<>c__DisplayClassa[TCode]
  ## Members
    * Void <WriteSprites>b__8(System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMSprite], System.IO.Stream, GMAssetCompiler.IFF, Int64)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.List`1[System.Collections.Generic.List`1[GMAssetCompiler.TexturePageEntry]] tpeEntries
    * Int32 nIndex
    * GMAssetCompiler.WADSaver`1[TCode] <>4__this
    * System.IO.Stream _s
# GMAssetCompiler.WADSaver`1+<>c__DisplayClass11[TCode]
  ## Members
    * Void <WriteScripts>b__10(System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMScript], System.IO.Stream, GMAssetCompiler.IFF, Int64)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 count
# GMAssetCompiler.WADSaver`1+<>c__DisplayClass14[TCode]
  ## Members
    * Void <WriteShaders>b__13(System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMShader], System.IO.Stream, GMAssetCompiler.IFF, Int64)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * GMAssetCompiler.WADSaver`1[TCode] <>4__this
    * System.IO.Stream _s
# GMAssetCompiler.WADSaver`1+<>c__DisplayClass18[TCode]
  ## Members
    * Void <WriteFonts>b__17(GMAssetCompiler.GMGlyph, System.IO.Stream, GMAssetCompiler.IFF, Int64)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Double scaleX
    * Double scaleY
# GMAssetCompiler.WADSaver`1+<>c__DisplayClass1b[TCode]
  ## Members
    * Void <WriteGMEvent>b__1a(GMAssetCompiler.GMAction, System.IO.Stream, GMAssetCompiler.IFF, Int64)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * GMAssetCompiler.WADSaver`1[TCode] <>4__this
    * GMAssetCompiler.GMEvent _event
# GMAssetCompiler.WADSaver`1+<>c__DisplayClass29[TCode]
  ## Members
    * Void <WriteRooms>b__21(System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMRoom], System.IO.Stream, GMAssetCompiler.IFF, Int64)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * GMAssetCompiler.WADSaver`1[TCode] <>4__this
    * System.IO.Stream _s
# GMAssetCompiler.WADSaver`1+<>c__DisplayClass29+<>c__DisplayClass2f[TCode]
  ## Members
    * Void <WriteRooms>b__26(GMAssetCompiler.GMLayerBase, System.IO.Stream, GMAssetCompiler.IFF, Int64)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c__DisplayClass29 CS$<>8__locals2a
    * GMAssetCompiler.IFF __iff
# GMAssetCompiler.WADSaver`1+<>c__DisplayClass34[TCode]
  ## Members
    * Void <WriteTextures>b__33(GMAssetCompiler.TexturesBlock, System.IO.Stream, GMAssetCompiler.IFF, Int64)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.List`1[System.Int32] patchoffsets
# GMAssetCompiler.WADSaver`1+<>c__DisplayClass39[TCode]
  ## Members
    * Void <WriteTexturePages>b__37(GMAssetCompiler.TexturePageEntry, System.IO.Stream, GMAssetCompiler.IFF, Int64)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 count
# GMAssetCompiler.WADSaver`1+<>c__DisplayClass3e[TCode]
  ## Members
    * Void <WriteStrings>b__3d(GMAssetCompiler.IFFString, System.IO.Stream, GMAssetCompiler.IFF, Int64)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 count
    * System.IO.Stream _s
# GMAssetCompiler.Program+<>c__DisplayClass1
  ## Members
    * Void <CheckSecurity>b__0(System.Object)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String exePath
    * System.String GameMakerEXE
    * System.String updaterEXE
# GMAssetCompiler.Program+<>c__DisplayClass92
  ## Members
    * System.String <SubstituteEnv>b__91(System.Text.RegularExpressions.Match)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.Dictionary`2[System.String,System.String] _env
# GMAssetCompiler.Program+<>c__DisplayClass96`2[R,T]
  ## Members
    * Void <ParallelExec>b__94(System.Object)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 nNumProcesses
    * System.Collections.Generic.List`1[R] results
    * System.Collections.Generic.IList`1[T] _list
    * Del_ParallelExec`2 _delegate
# GMAssetCompiler.Program+<>c__DisplayClass9b
  ## Members
    * Byte <MD5StringToByteArray>b__99(Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String hex
# GMAssetCompiler.IFFSaver+<>c__DisplayClass1
  ## Members
    * Void <WriteCode>b__0(IFFSaverCodeEntry, System.IO.Stream, GMAssetCompiler.IFF, Int64)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.List`1[System.Byte[]] bytes
    * Int64 offsetCode
    * Int32 count
    * GMAssetCompiler.IFFSaver <>4__this
    * System.IO.Stream _s
# GMAssetCompiler.IFFSaver+<>c__DisplayClass4
  ## Members
    * Void <WriteDebugScripts>b__3(IFFSaverCodeEntry, System.IO.Stream, GMAssetCompiler.IFF, Int64)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.Stream _s
# GMAssetCompiler.IFFSaver+<>c__DisplayClassb
  ## Members
    * Void <WriteDebugInstNames>b__a(System.String, System.IO.Stream, GMAssetCompiler.IFF, Int64)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.Stream _s
# <PrivateImplementationDetails>{4184FEE6-43B8-4B01-9762-CC6ADB80E913}+__StaticArrayInitTypeSize=40
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
# <PrivateImplementationDetails>{4184FEE6-43B8-4B01-9762-CC6ADB80E913}+__StaticArrayInitTypeSize=6
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
# <PrivateImplementationDetails>{4184FEE6-43B8-4B01-9762-CC6ADB80E913}+__StaticArrayInitTypeSize=36
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
