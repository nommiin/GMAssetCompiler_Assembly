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
    * Int32 get_tpeindex()
    * Void set_tpeindex(Int32)
    * Void SetImageData(Byte[])
    * Void SetImageData(SWFReader.SWFRGB15[])
    * Void SetImageData(SWFReader.SWFRGB[])
    * Void SetImageData(SWFReader.SWFRGBA[])
    * Void SetAlphaData(Byte[])
    * Void SetColourTableData(SWFReader.SWFRGB[])
    * Void SetColourTableData(SWFReader.SWFRGBA[])
    * Void Write(System.IO.Stream)
    * System.Drawing.Bitmap GetDecodedBitmap(Byte[])
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
    * Int32 tpeindex
    * SWFReader.eDictionaryItemType type
    * Int32 Id
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
    * UInt32 GetUintCol()
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
    * Int32 get_tpeindex()
    * Void set_tpeindex(Int32)
    * Boolean Matches(SWFReader.FillStyleData)
    * Void AddRecord(Int32, Byte, Byte, Byte, Byte)
    * Void SortByRatio()
    * Void Write(System.IO.Stream)
    * System.Drawing.Bitmap GetGradientBitmap()
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
    * Int32 tpeindex
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
    * Void MultF(SWFReader.Vec2f, Single ByRef, Single ByRef)
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
    * System.Collections.Generic.List`1[SWFReader.TriangulatorSnapshot] get_DebugSnapshots()
    * Void set_DebugSnapshots(System.Collections.Generic.List`1[SWFReader.TriangulatorSnapshot])
    * Int32 get_CurrSnapshot()
    * Void set_CurrSnapshot(Int32)
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
    * System.Collections.Generic.List`1[SWFReader.TriangulatorSnapshot] DebugSnapshots
    * Int32 CurrSnapshot
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
    * Boolean DrawingSnapshots
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
# SWFReader.SwfBitmapEntry
  ## Members
    * System.Drawing.Bitmap get_Image()
    * Void set_Image(System.Drawing.Bitmap)
    * Boolean get_SeperateTexturePage()
    * Void set_SeperateTexturePage(Boolean)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Drawing.Bitmap Image
    * Boolean SeperateTexturePage
# SWFReader.BuildShapeDataTask
  ## Members
    * SWFReader.Shape get_m_Shape()
    * Void set_m_Shape(SWFReader.Shape)
    * Single get_m_ShapeTolerance()
    * Void set_m_ShapeTolerance(Single)
    * SWFReader.SWFDefineShapeTag get_m_ShapeTag()
    * Void set_m_ShapeTag(SWFReader.SWFDefineShapeTag)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * SWFReader.Shape m_Shape
    * Single m_ShapeTolerance
    * SWFReader.SWFDefineShapeTag m_ShapeTag
# SWFReader.SwfFile
  ## Members
    * Void Trace(System.String)
    * Void Trace(System.String, System.Object[])
    * SWFReader.ShapeData BuildShapeData(System.Collections.Generic.List`1[SWFReader.SWFShapeRecord], SWFReader.SWFShape, Int32, Single, Int32)
    * Void GenerateGlyphLayout(SWFReader.TextField, Int32, Byte, Byte, Byte, Byte)
    * Int32 CountTags(System.Collections.Generic.List`1[SWFReader.SWFBaseTag])
    * Int32 ParseTags(SWFReader.Sprite, System.Collections.Generic.List`1[SWFReader.SWFBaseTag], Int32)
    * System.Drawing.Bitmap GenerateWhiteBitmap()
    * Void GenerateBitmapInfo()
    * Void BuildYYSToStream(System.IO.Stream)
    * Byte[] GetSWFData(System.String, Boolean, Boolean, Int32, Int32, Int32, Int32, Int32, Int32, Boolean, Single)
    * Void Load(System.String, Boolean, Boolean, Boolean, Int32, Int32, Int32, Int32, Int32, Int32, Boolean, Single)
    * Void Save(System.String, Boolean, SWFReader.Rect)
    * Int32 GenerateImages(System.String, System.String, Int32, Int32, Single)
    * Int32 GenerateShapes(System.String, System.String, Int32, Int32, Single)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Byte[] JPEGtables
    * System.Collections.Generic.List`1[SWFReader.DictionaryItem] DictionaryItems
    * SWFReader.Sprite RootSprite
    * System.Collections.Generic.List`1[SWFReader.SwfBitmapEntry] bitmaps
    * SWFReader.Timeline timeline
    * Int32 statusFlags
    * Int32 totalNumTags
    * System.String[] SWFUsageStrings
    * Single ShapeTolerance
    * Boolean BigEndian
    * Int32 NumThreadsToUse
    * Int32 NumActiveThreads
    * System.Object CritObj
    * Int32 FileVersion
    * Int32 SWF_EXT_FLAG
    * Single GlyphTolerance
# SWFReader.SwfFile+<>c__DisplayClass31_0
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.List`1[SWFReader.BuildShapeDataTask] tasklist
    * Int32 tasksInFlight
    * SWFReader.SwfFile <>4__this
    * System.Threading.WaitCallback <>9__0
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
# SWFReader.SWFDoActionTag
  ## Members
    * Boolean Parse(SWFReader.BitwiseBinaryReader)
    * System.String Dump()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
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
# SWFReader.TriangulatorSnapshot
  ## Members
    * Int32[] get_tri()
    * Void set_tri(Int32[])
    * System.Collections.Generic.List`1[System.Int32] get_contourpoints()
    * Void set_contourpoints(System.Collections.Generic.List`1[System.Int32])
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(Int32[], Int32, Int32[])
    * Void .ctor(SWFReader.TriangulatorSnapshot)
    * Int32[] tri
    * System.Collections.Generic.List`1[System.Int32] contourpoints
# SWFReader.Triangulator
  ## Members
    * Single Area(System.Collections.Generic.List`1[SWFReader.Vec2])
    * Int64 AreaX2(System.Collections.Generic.List`1[SWFReader.Vec2])
    * Boolean InsideTriangle(Single, Single, Single, Single, Single, Single, Single, Single)
    * Int32[] PruneZeroAreaSegments(System.Collections.Generic.List`1[SWFReader.Vec2], Int32[], Int32)
    * Boolean Process(System.Collections.Generic.List`1[SWFReader.Vec2], System.Collections.Generic.List`1[System.Int32], System.Collections.Generic.List`1[SWFReader.TriangulatorSnapshot], Boolean)
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
# .
  ## Members
    * Int32 ()
    * Int32 ()
    * Void (Spine.AtlasPage, System.String)
    * Void (System.Object)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 Width
    * Int32 Height
# .
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
# .
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
# .
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
# .
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
# .
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
# .
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
# .
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
# .
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
# .
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
# .
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
# .
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
# .
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
# .
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
# .
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
# .
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
# .
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
# .
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
# .
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
# .
  ## Members
    * Void Add(System.String)
    * Void ()
    * Boolean (System.String)
    * Void (System.String[], Int32)
    * Boolean (System.String)
    * Int32 ()
    * Boolean ()
    * System.Collections.Generic.IEnumerator`1[System.String] ()
    * Int32 (System.String)
    * Void (Int32, System.String)
    * Void (Int32)
    * System.String (Int32)
    * Void (Int32, System.String)
    * System.Collections.Generic.List`1[System.String] ()
    * System.String[] ()
    * System.String ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Int32 Count
    * Boolean IsReadOnly
    * System.String Item [Int32]
# .
  ## Members
    * . ()
    * Void (.)
    * System.String ()
    * Void (System.String)
    * Int32 ()
    * Void (Int32)
    * NDesk.Options.OptionSet ()
    * . ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(NDesk.Options.OptionSet)
    * . Option
    * System.String OptionName
    * Int32 OptionIndex
    * NDesk.Options.OptionSet OptionSet
    * . OptionValues
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
# .
  ## Members
    * System.String ()
    * System.String ()
    * NDesk.Options.OptionValueType ()
    * Int32 ()
    * System.String[] ()
    * System.String[] ()
    * Void (.)
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
    * System.String ()
    * Void (System.Runtime.Serialization.SerializationInfo, System.Runtime.Serialization.StreamingContext)
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
    * Void GetObjectData(System.Runtime.Serialization.SerializationInfo, System.Runtime.Serialization.StreamingContext)
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
# .[,]
  ## Members
    * Void Invoke(, )
    * System.IAsyncResult BeginInvoke(, , System.AsyncCallback, System.Object)
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
    * System.Converter`2[System.String,System.String] ()
    * NDesk.Options.OptionSet Add(.)
    * NDesk.Options.OptionSet (System.String, System.Action`1[System.String])
    * NDesk.Options.OptionSet (System.String, System.String, System.Action`1[System.String])
    * NDesk.Options.OptionSet (System.String, .[System.String,System.String])
    * NDesk.Options.OptionSet (System.String, System.String, .[System.String,System.String])
    * NDesk.Options.OptionSet [](System.String, System.Action`1[])
    * NDesk.Options.OptionSet [](System.String, System.String, System.Action`1[])
    * NDesk.Options.OptionSet [,](System.String, .[,])
    * NDesk.Options.OptionSet [,](System.String, System.String, .[,])
    * System.Collections.Generic.List`1[System.String] (System.Collections.Generic.IEnumerable`1[System.String])
    * Void (System.IO.TextWriter)
    * System.Collections.Generic.IEqualityComparer`1[System.String] get_Comparer()
    * . get_Item(System.String)
    * Boolean Contains(System.String)
    * Boolean Remove(System.String)
    * Int32 get_Count()
    * . get_Item(Int32)
    * Void set_Item(Int32, .)
    * Void Add(.)
    * Void Clear()
    * Void CopyTo(.[], Int32)
    * Boolean Contains(.)
    * System.Collections.Generic.IEnumerator`1[.] GetEnumerator()
    * Int32 IndexOf(.)
    * Void Insert(Int32, .)
    * Boolean Remove(.)
    * Void RemoveAt(Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(System.Converter`2[System.String,System.String])
    * System.Converter`2[System.String,System.String] MessageLocalizer
    * System.Collections.Generic.IEqualityComparer`1[System.String] Comparer
    * . Item [System.String]
    * Int32 Count
    * . Item [Int32]
# NDesk.Options.OptionSet+
  ## Members
    * System.String ()
    * System.String ()
    * NDesk.Options.OptionValueType ()
    * Int32 ()
    * System.String[] ()
    * System.String[] ()
    * Void (.)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String, System.String, Int32, System.Action`1[.])
    * System.String Prototype
    * System.String Description
    * NDesk.Options.OptionValueType OptionValueType
    * Int32 MaxValueCount
# NDesk.Options.OptionSet+[]
  ## Members
    * System.String ()
    * System.String ()
    * NDesk.Options.OptionValueType ()
    * Int32 ()
    * System.String[] ()
    * System.String[] ()
    * Void (.)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String, System.String, System.Action`1[])
    * System.String Prototype
    * System.String Description
    * NDesk.Options.OptionValueType OptionValueType
    * Int32 MaxValueCount
# NDesk.Options.OptionSet+[,]
  ## Members
    * System.String ()
    * System.String ()
    * NDesk.Options.OptionValueType ()
    * Int32 ()
    * System.String[] ()
    * System.String[] ()
    * Void (.)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String, System.String, .[,])
    * System.String Prototype
    * System.String Description
    * NDesk.Options.OptionValueType OptionValueType
    * Int32 MaxValueCount
# NDesk.Options.OptionSet+<>c
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * System.Converter`2[System.String,System.String] <>9__0_0
# NDesk.Options.OptionSet+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Action`1[System.String] 
# NDesk.Options.OptionSet+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * .[System.String,System.String] 
# .
  ## Members
    * Byte[] ()
    * Void (Byte[])
    * Int32 ()
    * Void (Int32)
    * System.Collections.Generic.Dictionary`2[System.String,System.String] ()
    * Void (System.Collections.Generic.Dictionary`2[System.String,System.String])
    * Byte[] (System.String)
    * System.Collections.Generic.Dictionary`2[System.String,System.Object] (System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String)
    * Byte[] MD5
    * Int32 CRC
    * System.Collections.Generic.Dictionary`2[System.String,System.String] License
# .
  ## Members
    * System.Collections.Generic.List`1[System.Collections.Generic.List`1[System.String]] (System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
# GMAssetCompiler.GMAudioGroup
  ## Members
    * Int32 get_GroupIndex()
    * Void set_GroupIndex(Int32)
    * Int64 get_TargetMask()
    * System.String get_GroupName()
    * Void UpdateFromConfigDelta(System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void SetFromConfig(System.Collections.Generic.Dictionary`2[System.String,System.String])
    * System.String ()
    * System.Guid ()
    * Void Dispose()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, Int32, System.Xml.XmlNode)
    * Void .ctor(System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Int32 GroupIndex
    * Int64 TargetMask
    * System.String GroupName
    * System.String Name
    * System.Guid GUID
# .
  ## Members
    * System.String ()
    * System.Guid ()
    * Void Dispose()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.Guid GUID
    * System.Collections.Generic.Dictionary`2[System.Guid,.] 
# .
  ## Members
    * System.String ()
    * System.String ()
    * Void (System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String, System.String)
    * System.String ID
    * System.String Text
# .
  ## Members
    * System.String ()
    * System.String ()
    * System.Collections.Generic.List`1[.] ()
    * Void (., Boolean)
    * Void (.)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String, System.String, System.Collections.Generic.List`1[System.Collections.Generic.List`1[System.String]])
    * System.String Language
    * System.String Region
    * System.Collections.Generic.List`1[.] Entries
# .
  ## Members
    * System.String ()
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * System.String ()
    * System.Guid ()
    * Void Dispose()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(System.String, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * System.String Filename
    * System.Collections.Generic.List`1[.] Languages
    * System.String Name
    * System.Guid GUID
# .
  ## Members
    * System.String ()
    * System.String ()
    * System.String ()
    * System.String ()
    * System.Guid ()
    * Void Dispose()
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
    * GMAssetCompiler.eShaderType 
    * GMAssetCompiler.eShaderType 
    * GMAssetCompiler.eShaderType 
    * GMAssetCompiler.eShaderType 
    * GMAssetCompiler.eShaderType 
    * GMAssetCompiler.eShaderType 
    * GMAssetCompiler.eShaderType 
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
    * System.String ()
    * System.Guid ()
    * Void Dispose()
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
    * System.String ShaderBaseName
    * System.String VertexFilename
    * System.String FragmentFilename
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
    * System.String ShaderCacheDirName
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
# GMAssetCompiler.GMShader+<>c
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * System.Diagnostics.DataReceivedEventHandler <>9__146_0
    * System.Diagnostics.DataReceivedEventHandler <>9__146_1
# GMAssetCompiler.GMShader+<>c__DisplayClass147_0
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String tempstring
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
    * Int32 get_MipsToGenerate()
    * Void SetParentName(System.Collections.Generic.List`1[GMAssetCompiler.GMTextureGroup])
    * Void UpdateFromConfigDelta(System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * System.String ()
    * System.Guid ()
    * Void Dispose()
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
    * Int32 MipsToGenerate
    * System.String Name
    * System.Guid GUID
# .
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
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
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
    * GMAssetCompiler.eAction 
    * GMAssetCompiler.eAction 
    * GMAssetCompiler.eAction 
    * GMAssetCompiler.eAction 
    * GMAssetCompiler.eAction 
    * GMAssetCompiler.eAction 
    * GMAssetCompiler.eAction 
    * GMAssetCompiler.eAction 
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
    * GMAssetCompiler.eExecuteTypes 
    * GMAssetCompiler.eExecuteTypes 
    * GMAssetCompiler.eExecuteTypes 
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
    * GMAssetCompiler.eArgTypes 
    * GMAssetCompiler.eArgTypes 
    * GMAssetCompiler.eArgTypes 
    * GMAssetCompiler.eArgTypes 
    * GMAssetCompiler.eArgTypes 
    * GMAssetCompiler.eArgTypes 
    * GMAssetCompiler.eArgTypes 
    * GMAssetCompiler.eArgTypes 
    * GMAssetCompiler.eArgTypes 
    * GMAssetCompiler.eArgTypes 
    * GMAssetCompiler.eArgTypes 
    * GMAssetCompiler.eArgTypes 
    * GMAssetCompiler.eArgTypes 
    * GMAssetCompiler.eArgTypes 
    * GMAssetCompiler.eArgTypes 
    * GMAssetCompiler.eArgTypes 
    * GMAssetCompiler.eArgTypes 
# GMAssetCompiler.GMAction
  ## Members
    * Int32 get_LibID()
    * Void set_LibID(Int32)
    * Int32 get_ID()
    * Void set_ID(Int32)
    * GMAssetCompiler.eAction get_Kind()
    * Void set_Kind(GMAssetCompiler.eAction)
    * Boolean get_UseRelative()
    * Void set_UseRelative(Boolean)
    * Boolean get_IsQuestion()
    * Void set_IsQuestion(Boolean)
    * Boolean get_UseApplyTo()
    * Void set_UseApplyTo(Boolean)
    * GMAssetCompiler.eExecuteTypes get_ExeType()
    * Void set_ExeType(GMAssetCompiler.eExecuteTypes)
    * System.String get_Code()
    * Void set_Code(System.String)
    * Int32 get_ArgumentCount()
    * Void set_ArgumentCount(Int32)
    * System.Collections.Generic.IList`1[GMAssetCompiler.eArgTypes] get_ArgTypes()
    * Void set_ArgTypes(System.Collections.Generic.IList`1[GMAssetCompiler.eArgTypes])
    * Int32 get_Who()
    * Void set_Who(Int32)
    * Boolean get_Relative()
    * Void set_Relative(Boolean)
    * System.Collections.Generic.IList`1[System.String] get_Args()
    * Void set_Args(System.Collections.Generic.IList`1[System.String])
    * Boolean get_IsNot()
    * Void set_IsNot(Boolean)
    * Void ProcessFixups(GMAssetCompiler.GMAssets)
    * Void ReadFromJSON(System.Collections.Generic.Dictionary`2[System.String,System.Object], GMAssetCompiler.GMAssets)
    * Void Compile(GMAssetCompiler.GMAssets)
    * System.String ()
    * System.Guid ()
    * Void Dispose()
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
    * System.String Code
    * Int32 ArgumentCount
    * System.Collections.Generic.IList`1[GMAssetCompiler.eArgTypes] ArgTypes
    * Int32 Who
    * Boolean Relative
    * System.Collections.Generic.IList`1[System.String] Args
    * Boolean IsNot
    * System.String Name
    * System.Guid GUID
    * System.Collections.Generic.List`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMAction]] ms_ActionWhoFixups
# GMAssetCompiler.GMAssets
  ## Members
    * Void (System.Collections.Generic.Dictionary`2[System.String,System.Object], System.Collections.IList, .)
    * Void (System.IO.Stream)
    * Void (System.IO.Stream)
    * Void (System.IO.Stream)
    * Void (System.IO.Stream)
    * Void (System.IO.Stream)
    * Void (System.IO.Stream)
    * Void (System.IO.Stream)
    * Void (System.IO.Stream)
    * Void (System.IO.Stream)
    * Void (System.IO.Stream)
    * Void (System.IO.Stream)
    * Void (System.IO.Stream)
    * Void (System.IO.Stream)
    * Void (System.IO.Stream)
    * Void (System.IO.Stream)
    * Void (Int32, Byte[], Int64)
    * Void ()
    * UInt32 (System.Object)
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Boolean ()
    * Void (Boolean)
    * System.String ()
    * System.String ()
    * Void (System.String)
    * Int32 ()
    * Void (Int32)
    * System.Guid ()
    * Void (System.Guid)
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMExtension] ()
    * System.Collections.Generic.IList`1[.] ()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMSound]] ()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMSprite]] ()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMBackground]] ()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMPath]] ()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMScript]] ()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMShader]] ()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMFont]] ()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMTimeLine]] ()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMObject]] ()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMRoom]] ()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMDataFile]] ()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMAudioGroup]] ()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,.]] ()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMTrackView]] ()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMSprite]] ()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMBackground]] ()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMObject]] ()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMRoom]] ()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMScript]] ()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,.]] ()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMAudioGroup]] ()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMTextureGroup]] ()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMObjectProperty]] ()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMTrackView]] ()
    * System.Collections.Generic.Dictionary`2[System.Guid,System.Collections.Generic.Dictionary`2[System.String,System.Object]] ()
    * System.Collections.Generic.Dictionary`2[System.String,System.Object] ()
    * System.Collections.Generic.IList`1[System.Guid] ()
    * System.Collections.Generic.IList`1[System.Int32] ()
    * System.Collections.Generic.IList`1[System.Guid] ()
    * System.Collections.Generic.IList`1[System.Int32] ()
    * System.Collections.Generic.IList`1[System.Guid] ()
    * System.Collections.Generic.IList`1[System.String] ()
    * . ()
    * Int32 ()
    * Int32 ()
    * System.Collections.Generic.Dictionary`2[System.String,System.Collections.Generic.Dictionary`2[System.String,System.String]] ()
    * Void (System.Collections.Generic.Dictionary`2[System.String,System.Collections.Generic.Dictionary`2[System.String,System.String]])
    * System.Collections.Generic.Dictionary`2[System.String,System.Collections.Generic.Dictionary`2[System.String,System.String]] ()
    * Void (System.Collections.Generic.Dictionary`2[System.String,System.Collections.Generic.Dictionary`2[System.String,System.String]])
    * Int32 ()
    * Void (Int32)
    * Int64 ()
    * Void (Int64)
    * GMAssetCompiler.GMOptions ()
    * . ()
    * Boolean ()
    * Void (Boolean)
    * System.Collections.Generic.Dictionary`2[System.String,System.Collections.Generic.Dictionary`2[System.String,System.Object]] ()
    * Void (System.Collections.Generic.Dictionary`2[System.String,System.Collections.Generic.Dictionary`2[System.String,System.Object]])
    * Int32 (Int32)
    * Void ()
    * System.Collections.Generic.List`1[System.Object] (Newtonsoft.Json.JsonTextReader)
    * System.Collections.Generic.Dictionary`2[System.String,System.Object] (Newtonsoft.Json.JsonTextReader)
    * System.Collections.Generic.Dictionary`2[System.String,System.Object] (System.String)
    * System.String (System.String)
    * System.String (System.String)
    * System.String (System.String)
    * System.String (System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Int32 Magic
    * Int32 Version
    * Boolean Debug
    * System.String Name
    * System.String BaseDir
    * Int32 GameID
    * System.Guid GameGUID
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMExtension] Extensions
    * System.Collections.Generic.IList`1[.] Triggers
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
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,.]] Macros
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMTrackView]] TrackViews
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMSprite]] SpritesById
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMBackground]] BackgroundsById
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMObject]] ObjectsById
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMRoom]] RoomsById
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMScript]] ScriptsById
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,.]] MacrosById
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMAudioGroup]] AudioGroupsById
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMTextureGroup]] TextureGroupsById
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMObjectProperty]] ObjectPropertyById
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.Guid,GMAssetCompiler.GMTrackView]] TrackViewsById
    * System.Collections.Generic.Dictionary`2[System.Guid,System.Collections.Generic.Dictionary`2[System.String,System.Object]] AllResources
    * System.Collections.Generic.Dictionary`2[System.String,System.Object] RootFolder
    * System.Collections.Generic.IList`1[System.Guid] OrderedResources
    * System.Collections.Generic.IList`1[System.Int32] RoomOrder
    * System.Collections.Generic.IList`1[System.Guid] RoomOrderById
    * System.Collections.Generic.IList`1[System.Int32] ScriptOrder
    * System.Collections.Generic.IList`1[System.Guid] ScriptOrderById
    * System.Collections.Generic.IList`1[System.String] Libraries
    * . Help
    * Int32 RoomMaxId
    * Int32 RoomMaxTileId
    * System.Collections.Generic.Dictionary`2[System.String,System.Collections.Generic.Dictionary`2[System.String,System.String]] Configs
    * System.Collections.Generic.Dictionary`2[System.String,System.Collections.Generic.Dictionary`2[System.String,System.String]] ConfigConstants
    * Int32 ConfigIndex
    * Int64 FunctionClassifications
    * GMAssetCompiler.GMOptions Options
    * . Languages
    * Boolean DNDRemoved
    * System.Collections.Generic.Dictionary`2[System.String,System.Collections.Generic.Dictionary`2[System.String,System.Object]] YYFileContents
    * System.Collections.Generic.List`1[System.String] 
    * System.Collections.Generic.List`1[System.String] 
    * GMAssetCompiler.GMAssets+
    * GMAssetCompiler.GMAssets+
    * GMAssetCompiler.GMAssets+
# GMAssetCompiler.GMAssets+
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
    *  
    *  
    *  
    *  
    *  
    *  
    *  
    *  
    *  
    *  
    *  
    *  
# GMAssetCompiler.GMAssets+
  ## Members
    * System.Guid ()
    * Void (System.Guid)
    * System.Collections.Generic.Dictionary`2[System.String,System.Object] ()
    * Void (System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Guid id
    * System.Collections.Generic.Dictionary`2[System.String,System.Object] resource
# GMAssetCompiler.GMAssets+
  ## Members
    *  ()
    * Void ()
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(, System.String, System.String)
    *  Type
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
# GMAssetCompiler.GMAssets+<>c
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * System.Action`1[System.String] <>9__238_0
    * System.Func`2[System.Collections.Generic.KeyValuePair`2[System.String,System.Object],System.Boolean] <>9__250_0
    * System.Action`3[System.Collections.IList,System.Int32,System.Object] <>9__255_0
    * Factory`1 <>9__258_0
    * Factory`1 <>9__258_1
    * Factory`1 <>9__258_2
    * Factory`1 <>9__258_3
    * Factory`1 <>9__258_4
    * Factory`1 <>9__258_5
    * Factory`1 <>9__258_6
    * Factory`1 <>9__258_7
    * Factory`1 <>9__258_8
# GMAssetCompiler.GMAssets+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Guid 
# GMAssetCompiler.GMAssets+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Guid 
# GMAssetCompiler.GMBackground
  ## Members
    * Boolean ()
    * Boolean ()
    * Boolean ()
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * GMAssetCompiler.GMBitmap32 ()
    * Int32 ()
    * Int32 ()
    * Boolean ()
    * Boolean ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int64 ()
    * System.Collections.Generic.List`1[System.UInt32] ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * System.Collections.Generic.List`1[System.Int32] ()
    * Boolean ()
    * System.String ()
    * System.String ()
    * Void (GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * System.String ()
    * System.Guid ()
    * Void Dispose()
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
    * Boolean SpriteNoExport
    * GMAssetCompiler.GMBitmap32 Bitmap
    * Int32 Width
    * Int32 Height
    * Boolean HTile
    * Boolean VTile
    * Int32 Columns
    * Int32 SpriteIndex
    * Int32 Frames
    * Int32 TileCount
    * Int64 FrameLength
    * System.Collections.Generic.List`1[System.UInt32] FrameData
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
# GMAssetCompiler.GMBackground+<>c
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * System.Converter`2[System.Object,System.UInt32] <>9__106_0
# GMAssetCompiler.GMBitmap32
  ## Members
    * Int32 ()
    * Int32 ()
    * Byte[] ()
    * Void (GMAssetCompiler.GMBitmap32)
    * System.Drawing.Bitmap ()
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
    * System.String ()
    * System.String ()
    * Boolean ()
    * Int32 ()
    * Boolean ()
    * Byte[] ()
    * Int32 ()
    * System.String ()
    * Boolean ()
    * Boolean ()
    * Boolean ()
    * System.Collections.Generic.Dictionary`2[System.String,System.Int64] ()
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
    * System.Guid get_EventCollisionId()
    * System.Guid get_ObjectId()
    * Void set_ObjectId(System.Guid)
    * Void ReadFromJSON(System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * System.String CompressEvent(System.String, System.String)
    * System.String ()
    * System.Guid ()
    * Void Dispose()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(GMAssetCompiler.GMAssets, System.Xml.XmlNode)
    * Void .ctor(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void .ctor(GMAssetCompiler.GMAssets, System.IO.Stream)
    * Int32 CompiledIndex
    * System.Collections.Generic.List`1[GMAssetCompiler.GMAction] Actions
    * Int32 EventNum
    * Int32 EventType
    * System.Guid EventCollisionId
    * System.Guid ObjectId
    * System.String Name
    * System.Guid GUID
# GMAssetCompiler.FrameworkInfo
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Boolean 
    * System.String 
# GMAssetCompiler.GMExtension
  ## Members
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
    * System.Collections.Generic.Dictionary`2[System.String,System.Int64] get_ConfigOptions()
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
    * System.String get_SourceFileName()
    * System.String get_tvOSSourceDir()
    * Void set_tvOSSourceDir(System.String)
    * System.String get_tvOSClassName()
    * Void set_tvOSClassName(System.String)
    * System.String get_tvOSLinkerFlags()
    * Void set_tvOSLinkerFlags(System.String)
    * System.String get_tvOSCompilerFlags()
    * Void set_tvOSCompilerFlags(System.String)
    * System.Collections.Generic.IList`1[GMAssetCompiler.FrameworkInfo] get_tvosSystemFrameworks()
    * System.Collections.Generic.IList`1[GMAssetCompiler.FrameworkInfo] get_tvosThirdPartyFrameworks()
    * System.String ReplaceCRLF(System.String)
    * System.String RemoveCRLF(System.String)
    * Void SetFromJson(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * System.String ()
    * System.Guid ()
    * Void Dispose()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.String)
    * Void .ctor(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void .ctor(GMAssetCompiler.GMAssets, System.IO.Stream)
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
    * System.Collections.Generic.Dictionary`2[System.String,System.Int64] ConfigOptions
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
    * System.String SourceFileName
    * System.String tvOSSourceDir
    * System.String tvOSClassName
    * System.String tvOSLinkerFlags
    * System.String tvOSCompilerFlags
    * System.Collections.Generic.IList`1[GMAssetCompiler.FrameworkInfo] tvosSystemFrameworks
    * System.Collections.Generic.IList`1[GMAssetCompiler.FrameworkInfo] tvosThirdPartyFrameworks
    * System.String Name
    * System.Guid GUID
    * System.String iosPlistInject
    * System.String tvosPlistInject
# .
  ## Members
    * System.String ()
    * System.String ()
    * System.Guid ()
    * Void Dispose()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.Xml.XmlNode)
    * Void .ctor(GMAssetCompiler.GMAssets, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void .ctor(System.IO.Stream)
    * System.String Value
    * System.String Name
    * System.Guid GUID
# .
  ## Members
    * System.String ()
    * Int32 ()
    * Int32 ()
    * System.Collections.Generic.IList`1[System.Int32] ()
    * Int32 ()
    * Int32 ()
    * System.String ()
    * System.String ()
    * System.Guid ()
    * Void Dispose()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.Xml.XmlNode)
    * Void .ctor(GMAssetCompiler.GMAssets, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void .ctor(System.IO.Stream)
    * System.String ExtName
    * Int32 Kind
    * Int32 Id
    * System.Collections.Generic.IList`1[System.Int32] Args
    * Int32 ArgCount
    * Int32 ReturnType
    * System.String Help
    * System.String Name
    * System.Guid GUID
    * .+
# .+
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
    *  
    *  
# .
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
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
# GMAssetCompiler.GMExtensionInclude
  ## Members
    * System.String ()
    * System.String ()
    * Void (System.String)
    * Int32 ()
    * System.String ()
    * System.String ()
    * Boolean ()
    * System.Collections.Generic.IList`1[.] ()
    * System.Collections.Generic.IList`1[.] ()
    * System.Collections.Generic.Dictionary`2[System.String,System.Int64] ()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,System.Int64]] ()
    * Boolean ()
    * Void (Boolean)
    * Void (GMAssetCompiler.GMAssets, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * System.String ()
    * System.Guid ()
    * Void Dispose()
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
    * System.Collections.Generic.IList`1[.] Functions
    * System.Collections.Generic.IList`1[.] Constants
    * System.Collections.Generic.Dictionary`2[System.String,System.Int64] ConfigOptions
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,System.Int64]] ProxyFiles
    * Boolean Used
    * System.String Name
    * System.Guid GUID
# .
  ## Members
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 Other
    * Int32 Amount
# GMAssetCompiler.GMGlyph
  ## Members
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * Int32 ()
    * Void (Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(Int32, Int32, Int32, Int32, Int32, Int32, Int32, System.Collections.Generic.List`1[.])
    * Int32 X
    * Int32 Y
    * Int32 W
    * Int32 H
    * Int32 Shift
    * Int32 Offset
    * System.Collections.Generic.List`1[.] Kerning
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
    * System.String ()
    * System.Guid ()
    * Void Dispose()
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
# GMAssetCompiler.GMFont+<>c
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * System.Comparison`1[GMAssetCompiler.GMGlyph] <>9__57_0
    * System.Comparison`1[GMAssetCompiler.GMGlyph] <>9__60_0
# .
  ## Members
    * Int32 ()
    * Boolean ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Boolean ()
    * Boolean ()
    * Boolean ()
    * Boolean ()
    * System.String ()
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
    * Single ()
    * Void (Single)
    * Single ()
    * Void (Single)
    * System.String ()
    * System.Guid ()
    * Void Dispose()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Single X
    * Single Y
    * System.String Name
    * System.Guid GUID
# GMAssetCompiler.SubTypeAndEvent
  ## Members
    * Int32 ()
    * Void (Int32)
    * GMAssetCompiler.GMEvent ()
    * Void (GMAssetCompiler.GMEvent)
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
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMEvent] get_EventList()
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
    * System.Collections.Generic.List`1[GMAssetCompiler.GMObjectProperty] get_Properties()
    * System.Collections.Generic.List`1[GMAssetCompiler.GMOverriddenProperty] get_PropertyOverrides()
    * Void ProcessFixups(GMAssetCompiler.GMAssets)
    * Void VerifyObjectVariables(GMAssetCompiler.GMAssets)
    * System.Collections.Generic.IEnumerable`1[System.String] GetUndefinedVariables(GMAssetCompiler.GMAssets, GMAssetCompiler.GMObject, System.Collections.Generic.List`1[System.String], System.String)
    * GMAssetCompiler.GMObjectProperty GetPropertyInParent(GMAssetCompiler.GMAssets, Int32, System.String)
    * GMAssetCompiler.GMOverriddenProperty GetOverriddenProperty(GMAssetCompiler.GMAssets, Int32, System.Guid)
    * Int32 GMX_FindObject(System.String, System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMObject]])
    * System.Collections.Generic.IList`1[System.Collections.Generic.IList`1[GMAssetCompiler.SubTypeAndEvent]] CreateEvents(GMAssetCompiler.GMAssets, System.Xml.XmlNode)
    * Void SetFromJson(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void GeneratePreCreateEvent(GMAssetCompiler.GMAssets)
    * Void GenerateReevaluateVariables(System.Text.StringBuilder, GMAssetCompiler.GMAssets, GMAssetCompiler.GMObject, System.Collections.Generic.List`1[System.String])
    * Void AppendPrecreateVariable(System.Text.StringBuilder, System.String, GMAssetCompiler.eObjectPropertyType, System.String, Boolean, System.String, GMAssetCompiler.GMObjectProperty, System.String)
    * System.String FormatVariableValue(GMAssetCompiler.eObjectPropertyType, Boolean, System.String, System.String, GMAssetCompiler.GMObjectProperty, System.String)
    * Void AdjustPhysicsVertex(GMAssetCompiler.GMAssets, GMAssetCompiler.GMPhysicsShapeVertex)
    * GMAssetCompiler.SubTypeAndEvent SubTypeAndEventFromEvent(GMAssetCompiler.GMAssets, GMAssetCompiler.GMEvent)
    * Void UpdateEventCode(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.List`1[System.String])
    * System.String GetEventName_Simple(Int32, Int32, System.String)
    * System.String ()
    * System.Guid ()
    * Void Dispose()
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
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMEvent] EventList
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
    * System.Collections.Generic.List`1[GMAssetCompiler.GMObjectProperty] Properties
    * System.Collections.Generic.List`1[GMAssetCompiler.GMOverriddenProperty] PropertyOverrides
    * System.String Name
    * System.Guid GUID
    * System.String ResourceTreePath
# GMAssetCompiler.GMObject+<>c__DisplayClass111_0
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String ident
# GMAssetCompiler.GMObject+<>c__DisplayClass127_0
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String filename
# GMAssetCompiler.GMObjectProperty
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * System.Guid id
    * System.String name
    * System.String value
    * GMAssetCompiler.eObjectPropertyType type
    * Boolean multiselect
# GMAssetCompiler.GMOverriddenProperty
  ## Members
    * GMAssetCompiler.GMObjectProperty GetProperty(GMAssetCompiler.GMAssets)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * System.Guid propertyId
    * System.String value
# GMAssetCompiler.eObjectPropertyType
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
    * GMAssetCompiler.eObjectPropertyType Real
    * GMAssetCompiler.eObjectPropertyType Integer
    * GMAssetCompiler.eObjectPropertyType String
    * GMAssetCompiler.eObjectPropertyType Boolean
    * GMAssetCompiler.eObjectPropertyType Expression
    * GMAssetCompiler.eObjectPropertyType Resource
    * GMAssetCompiler.eObjectPropertyType List
    * GMAssetCompiler.eObjectPropertyType Color
# GMAssetCompiler.GMOptions
  ## Members
    * System.String get_Win8AnalyticsId()
    * Void set_Win8AnalyticsId(System.String)
    * System.String get_VersionMajor()
    * Void set_VersionMajor(System.String)
    * System.String get_VersionMinor()
    * Void set_VersionMinor(System.String)
    * System.String get_VersionBuild()
    * Void set_VersionBuild(System.String)
    * System.String get_VersionRevision()
    * Void set_VersionRevision(System.String)
    * Int32 get_SteamAppId()
    * Void set_SteamAppId(Int32)
    * Boolean get_SteamBuild()
    * Void set_SteamBuild(Boolean)
    * System.Collections.Generic.List`1[GMAssetCompiler.GMTextureGroup] get_TextureGroups()
    * Int32 get_MipsFor3DTextures()
    * Void SetFromConfig(System.Collections.Generic.Dictionary`2[System.String,System.String], System.String)
    * Void SetFromJson(GMAssetCompiler.GMAssets, System.Collections.Generic.Dictionary`2[System.String,System.Object], System.String)
    * Void UpdateFromConfigDelta(GMAssetCompiler.GMAssets, System.Guid, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void WriteToJson(System.String)
    * Boolean get_DebugEnabled()
    * System.String get_Config()
    * Boolean get_UseNewAudio()
    * Boolean get_UseFastCollision()
    * Boolean get_FastCollisionCompatibility()
    * Boolean get_OutputDebugToConsole()
    * System.String get_html5jsprepend()
    * System.String get_html5outputfile()
    * System.String get_html5_included_indexhtml()
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
    * Int32 get_SleepMargin()
    * Boolean get_NoButtons()
    * Int32 get_Sync_Vertex()
    * Boolean get_UseRetina()
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
    * System.String ()
    * System.Guid ()
    * Void Dispose()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Boolean DebugEnabled
    * System.String Config
    * Boolean UseNewAudio
    * Boolean UseFastCollision
    * Boolean FastCollisionCompatibility
    * Boolean OutputDebugToConsole
    * System.String html5jsprepend
    * System.String html5outputfile
    * System.String html5_included_indexhtml
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
    * Int32 SleepMargin
    * Boolean NoButtons
    * Int32 Sync_Vertex
    * Boolean UseRetina
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
    * Int32 SteamAppId
    * Boolean SteamBuild
    * System.Collections.Generic.List`1[GMAssetCompiler.GMTextureGroup] TextureGroups
    * Int32 MipsFor3DTextures
    * System.String Name
    * System.Guid GUID
    * System.Collections.Generic.List`1[GMAssetCompiler.GMOptions+ConfigDeltaFile] ConfigDeltaFiles
    * Double GameSpeed
    * Boolean AllowStatistics
    * UInt32 DrawColour
    * System.Collections.Generic.Dictionary`2[System.String,System.String] ConfigDictionary
    * GMAssetCompiler.GMOptions+ConfigDeltaFile
# GMAssetCompiler.GMOptions+ConfigDeltaFile
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String resourceType
    * System.String filePath
# GMAssetCompiler.GMOptions+<>c
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * System.Predicate`1[System.String] <>9__306_0
# GMAssetCompiler.GMPathPoint
  ## Members
    * Double ()
    * Double ()
    * Double ()
    * System.String ()
    * System.Guid ()
    * Void Dispose()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(Double, Double, Double)
    * Void .ctor(System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Double X
    * Double Y
    * Double Speed
    * System.String Name
    * System.Guid GUID
# GMAssetCompiler.GMPath
  ## Members
    * Int32 get_Kind()
    * Boolean get_Closed()
    * Int32 get_Precision()
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMPathPoint] get_Points()
    * Int32 get_BackRoom()
    * Boolean get_HSnap()
    * Boolean get_VSnap()
    * Void SetFromJson(GMAssetCompiler.GMAssets, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * System.String ()
    * System.Guid ()
    * Void Dispose()
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
# .
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
    * . 
    * . 
# GMAssetCompiler.GMRoomSettings
  ## Members
    * Void ReadFromJSON(System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * System.String ()
    * System.Guid ()
    * Void Dispose()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.Guid GUID
    * Int32 Width
    * Int32 Height
    * Int32 Speed
    * Boolean Persistent
# GMAssetCompiler.GMRoomViewSettings
  ## Members
    * Void ReadFromJSON(System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * System.String ()
    * System.Guid ()
    * Void Dispose()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.Guid GUID
    * Boolean EnableViews
    * Boolean ViewClearScreen
    * Boolean ClearDisplayBuffer
# GMAssetCompiler.GMRoomPhysicsSettings
  ## Members
    * Void ReadFromJSON(System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * System.String ()
    * System.Guid ()
    * Void Dispose()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.Guid GUID
    * Boolean PhysicsWorld
    * Single PhysicsWorldGravityX
    * Single PhysicsWorldGravityY
    * Single PhysicsWorldPixToMeters
# GMAssetCompiler.GMBack
  ## Members
    * Boolean ()
    * Boolean ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Boolean ()
    * Boolean ()
    * Int32 ()
    * Int32 ()
    * Double ()
    * Double ()
    * Int32 ()
    * Double ()
    * Boolean ()
    * Single ()
    * Int32 ()
    * Double ()
    * Double ()
    * Boolean ()
    * Void (System.Collections.Generic.Dictionary`2[System.String,System.Object], GMAssetCompiler.GMAssets)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.Xml.XmlNode)
    * Void .ctor(Boolean)
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
    * Single AnimationFPS
    * Int32 AnimationSpeedType
    * Double FirstFrame
    * Double FrameSpeed
    * Boolean SpriteBackgrounds
# GMAssetCompiler.GMView
  ## Members
    * Boolean ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Double ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
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
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Double ()
    * Double ()
    * Int32 ()
    * Double ()
    * Boolean ()
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
    * Boolean Ignore
# GMAssetCompiler.GMSpriteGraphic
  ## Members
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Double ()
    * Double ()
    * Int32 ()
    * Double ()
    * Single ()
    * Single ()
    * Int32 ()
    * Single ()
    * Single ()
    * Boolean ()
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
    * Single AnimationFPS
    * Int32 AnimationSpeedType
    * Single FrameIndex
    * Single Rotation
    * Boolean Ignore
# GMAssetCompiler.GMInstance
  ## Members
    * System.Guid ()
    * Boolean ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * Double ()
    * Double ()
    * UInt32 ()
    * Double ()
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * System.Collections.Generic.List`1[GMAssetCompiler.GMOverriddenProperty] ()
    * Boolean ()
    * Void (GMAssetCompiler.GMAssets)
    * Void (GMAssetCompiler.GMAssets)
    * Void (GMAssetCompiler.GMAssets)
    * System.String ()
    * System.Guid ()
    * Void Dispose()
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
    * System.String PreCreateCode
    * Double ScaleX
    * Double ScaleY
    * UInt32 Colour
    * Double Rotation
    * Int32 CompiledIndex
    * Int32 CompiledPreCreateIndex
    * System.Collections.Generic.List`1[GMAssetCompiler.GMOverriddenProperty] PropertyOverrides
    * Boolean Ignore
    * System.String Name
    * System.Guid GUID
    * System.Collections.Generic.Dictionary`2[System.Guid,GMAssetCompiler.GMInstance] 
# GMAssetCompiler.GMInstance+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * GMAssetCompiler.GMOverriddenProperty 
# GMAssetCompiler.GMInstance+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * GMAssetCompiler.GMInstance 
# GMAssetCompiler.GMRoomMakerSettings
  ## Members
    * Boolean ()
    * Void (Boolean)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * System.String ()
    * System.Guid ()
    * Void Dispose()
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
    * System.String Name
    * System.Guid GUID
# .
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
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
# GMAssetCompiler.GMLayerBase
  ## Members
    * GMAssetCompiler.GMRoom ()
    * Void (GMAssetCompiler.GMRoom)
    * System.Collections.Generic.List`1[GMAssetCompiler.GMLayerBase] ()
    * Void (System.Collections.Generic.List`1[GMAssetCompiler.GMLayerBase])
    * Int32 ()
    * Void (Int32)
    * . ()
    * Void (.)
    * Int32 ()
    * Void (Int32)
    * Double ()
    * Void (Double)
    * Double ()
    * Void (Double)
    * Double ()
    * Void (Double)
    * Double ()
    * Void (Double)
    * Boolean ()
    * Void (Boolean)
    * Void ReadFromJSON(System.Collections.Generic.Dictionary`2[System.String,System.Object], GMAssetCompiler.GMAssets)
    * Void Dispose()
    * System.String ()
    * System.Guid ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String, Int32, GMAssetCompiler.GMRoom)
    * GMAssetCompiler.GMRoom Room
    * System.Collections.Generic.List`1[GMAssetCompiler.GMLayerBase] SubLayers
    * Int32 Id
    * . LayerType
    * Int32 Depth
    * Double xoffset
    * Double yoffset
    * Double hspeed
    * Double vspeed
    * Boolean visible
    * System.String Name
    * System.Guid GUID
# GMAssetCompiler.GMFolderLayer
  ## Members
    * GMAssetCompiler.GMRoom ()
    * Void (GMAssetCompiler.GMRoom)
    * System.Collections.Generic.List`1[GMAssetCompiler.GMLayerBase] ()
    * Void (System.Collections.Generic.List`1[GMAssetCompiler.GMLayerBase])
    * Int32 ()
    * Void (Int32)
    * . ()
    * Void (.)
    * Int32 ()
    * Void (Int32)
    * Double ()
    * Void (Double)
    * Double ()
    * Void (Double)
    * Double ()
    * Void (Double)
    * Double ()
    * Void (Double)
    * Boolean ()
    * Void (Boolean)
    * Void ReadFromJSON(System.Collections.Generic.Dictionary`2[System.String,System.Object], GMAssetCompiler.GMAssets)
    * Void Dispose()
    * System.String ()
    * System.Guid ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String, Int32, GMAssetCompiler.GMRoom)
    * GMAssetCompiler.GMRoom Room
    * System.Collections.Generic.List`1[GMAssetCompiler.GMLayerBase] SubLayers
    * Int32 Id
    * . LayerType
    * Int32 Depth
    * Double xoffset
    * Double yoffset
    * Double hspeed
    * Double vspeed
    * Boolean visible
    * System.String Name
    * System.Guid GUID
# GMAssetCompiler.GMBackgroundLayer
  ## Members
    * Void ReadFromJSON(System.Collections.Generic.Dictionary`2[System.String,System.Object], GMAssetCompiler.GMAssets)
    * GMAssetCompiler.GMRoom ()
    * Void (GMAssetCompiler.GMRoom)
    * System.Collections.Generic.List`1[GMAssetCompiler.GMLayerBase] ()
    * Void (System.Collections.Generic.List`1[GMAssetCompiler.GMLayerBase])
    * Int32 ()
    * Void (Int32)
    * . ()
    * Void (.)
    * Int32 ()
    * Void (Int32)
    * Double ()
    * Void (Double)
    * Double ()
    * Void (Double)
    * Double ()
    * Void (Double)
    * Double ()
    * Void (Double)
    * Boolean ()
    * Void (Boolean)
    * Void Dispose()
    * System.String ()
    * System.Guid ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String, Int32, GMAssetCompiler.GMRoom)
    * GMAssetCompiler.GMRoom Room
    * System.Collections.Generic.List`1[GMAssetCompiler.GMLayerBase] SubLayers
    * Int32 Id
    * . LayerType
    * Int32 Depth
    * Double xoffset
    * Double yoffset
    * Double hspeed
    * Double vspeed
    * Boolean visible
    * System.String Name
    * System.Guid GUID
    * GMAssetCompiler.GMBack Background
# GMAssetCompiler.GMInstanceLayer
  ## Members
    * Void ReadFromJSON(System.Collections.Generic.Dictionary`2[System.String,System.Object], GMAssetCompiler.GMAssets, GMAssetCompiler.GMRoom)
    * Void Dispose()
    * GMAssetCompiler.GMRoom ()
    * Void (GMAssetCompiler.GMRoom)
    * System.Collections.Generic.List`1[GMAssetCompiler.GMLayerBase] ()
    * Void (System.Collections.Generic.List`1[GMAssetCompiler.GMLayerBase])
    * Int32 ()
    * Void (Int32)
    * . ()
    * Void (.)
    * Int32 ()
    * Void (Int32)
    * Double ()
    * Void (Double)
    * Double ()
    * Void (Double)
    * Double ()
    * Void (Double)
    * Double ()
    * Void (Double)
    * Boolean ()
    * Void (Boolean)
    * Void ReadFromJSON(System.Collections.Generic.Dictionary`2[System.String,System.Object], GMAssetCompiler.GMAssets)
    * System.String ()
    * System.Guid ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String, Int32, GMAssetCompiler.GMRoom)
    * GMAssetCompiler.GMRoom Room
    * System.Collections.Generic.List`1[GMAssetCompiler.GMLayerBase] SubLayers
    * Int32 Id
    * . LayerType
    * Int32 Depth
    * Double xoffset
    * Double yoffset
    * Double hspeed
    * Double vspeed
    * Boolean visible
    * System.String Name
    * System.Guid GUID
    * System.Collections.Generic.List`1[System.Int32] InstanceIDs
    * System.Collections.Generic.List`1[GMAssetCompiler.GMInstance] Instances
# GMAssetCompiler.GMInstanceLayer+<>c__DisplayClass3_0
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.List`1[GMAssetCompiler.GMInstance] instancesStore
# GMAssetCompiler.GMAssetLayer
  ## Members
    * Void ReadFromJSON(System.Collections.Generic.Dictionary`2[System.String,System.Object], GMAssetCompiler.GMAssets)
    * GMAssetCompiler.GMRoom ()
    * Void (GMAssetCompiler.GMRoom)
    * System.Collections.Generic.List`1[GMAssetCompiler.GMLayerBase] ()
    * Void (System.Collections.Generic.List`1[GMAssetCompiler.GMLayerBase])
    * Int32 ()
    * Void (Int32)
    * . ()
    * Void (.)
    * Int32 ()
    * Void (Int32)
    * Double ()
    * Void (Double)
    * Double ()
    * Void (Double)
    * Double ()
    * Void (Double)
    * Double ()
    * Void (Double)
    * Boolean ()
    * Void (Boolean)
    * Void Dispose()
    * System.String ()
    * System.Guid ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String, Int32, GMAssetCompiler.GMRoom)
    * GMAssetCompiler.GMRoom Room
    * System.Collections.Generic.List`1[GMAssetCompiler.GMLayerBase] SubLayers
    * Int32 Id
    * . LayerType
    * Int32 Depth
    * Double xoffset
    * Double yoffset
    * Double hspeed
    * Double vspeed
    * Boolean visible
    * System.String Name
    * System.Guid GUID
    * System.Collections.Generic.List`1[GMAssetCompiler.GMTile] Tiles
    * System.Collections.Generic.List`1[GMAssetCompiler.GMSpriteGraphic] Sprites
# GMAssetCompiler.GMTileLayer
  ## Members
    * UInt32 TranslateTiledata(UInt32)
    * Void ReadFromJSON(System.Collections.Generic.Dictionary`2[System.String,System.Object], GMAssetCompiler.GMAssets)
    * GMAssetCompiler.GMRoom ()
    * Void (GMAssetCompiler.GMRoom)
    * System.Collections.Generic.List`1[GMAssetCompiler.GMLayerBase] ()
    * Void (System.Collections.Generic.List`1[GMAssetCompiler.GMLayerBase])
    * Int32 ()
    * Void (Int32)
    * . ()
    * Void (.)
    * Int32 ()
    * Void (Int32)
    * Double ()
    * Void (Double)
    * Double ()
    * Void (Double)
    * Double ()
    * Void (Double)
    * Double ()
    * Void (Double)
    * Boolean ()
    * Void (Boolean)
    * Void Dispose()
    * System.String ()
    * System.Guid ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String, Int32, GMAssetCompiler.GMRoom)
    * GMAssetCompiler.GMRoom Room
    * System.Collections.Generic.List`1[GMAssetCompiler.GMLayerBase] SubLayers
    * Int32 Id
    * . LayerType
    * Int32 Depth
    * Double xoffset
    * Double yoffset
    * Double hspeed
    * Double vspeed
    * Boolean visible
    * System.String Name
    * System.Guid GUID
    * Int32 Index
    * Int32 MapWidth
    * Int32 MapHeight
    * Int32 TileSize
    * Int32 TileHSep
    * Int32 TileVSep
    * Int32 TileColumns
    * System.Collections.Generic.List`1[System.UInt32] Tiles
    * UInt32 TileBitMask_All
    * Int32 RnTileBit_Inherit
    * Int32 RnTileBit_Rotate90
    * Int32 RnTileBit_Flip
    * Int32 RnTileBit_Mirror
    * Int32 RnTileBit_TileIndex
    * Int32 RnTileBit_ColourIndex
    * Int32 RnTileBitRange_TileIndex
    * Int32 RnTileBitRange_ColourIndex
    * UInt32 RnTileMaxValue_TileIndex
    * UInt32 RnTileMaxValue_ColourIndex
    * UInt32 RnTileBitMask_Inherit
    * UInt32 RnTileBitMask_Flip
    * UInt32 RnTileBitMask_Mirror
    * UInt32 RnTileBitMask_Rotate90
    * UInt32 RnTileBitMask_TileIndex
    * UInt32 RnTileBitMask_ColourIndex
# GMAssetCompiler.GMRoom
  ## Members
    * Boolean get_InheritCode()
    * Void set_InheritCode(Boolean)
    * System.Guid get_ParentGUID()
    * Void set_ParentGUID(System.Guid)
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
    * System.Collections.Generic.IList`1[System.Guid] get_InstanceCreationOrder()
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
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMLayerBase] get_BaseLayers()
    * Int32 get_HSnap()
    * Void set_HSnap(Int32)
    * Int32 get_VSnap()
    * Void set_VSnap(Int32)
    * Boolean get_Isometric()
    * Void set_Isometric(Boolean)
    * GMAssetCompiler.GMRoomMakerSettings get_MakerSettings()
    * Void set_MakerSettings(GMAssetCompiler.GMRoomMakerSettings)
    * System.String GetRoomDirectory()
    * Void SetFromJson(GMAssetCompiler.GMAssets, System.Collections.Generic.Dictionary`2[System.String,System.Object], Boolean)
    * Void UpdateCreationCode(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.List`1[System.String])
    * Void ReadRoomSettings(System.Object)
    * Void ReadPhysicsSettings(System.Object)
    * Void ReadViewSettings(System.Object)
    * Void RebuildLayers()
    * Void InsertLayer(GMAssetCompiler.GMAssets, System.Collections.Generic.Dictionary`2[System.String,System.Object], Int32)
    * Void ProcessFixups(GMAssetCompiler.GMAssets)
    * System.String ()
    * System.Guid ()
    * Void Dispose()
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
    * System.Guid ParentGUID
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
    * System.Collections.Generic.IList`1[System.Guid] InstanceCreationOrder
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
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMLayerBase] BaseLayers
    * Int32 HSnap
    * Int32 VSnap
    * Boolean Isometric
    * GMAssetCompiler.GMRoomMakerSettings MakerSettings
    * System.String Name
    * System.Guid GUID
    * GMAssetCompiler.GMRoomSettings RoomSettings
    * GMAssetCompiler.GMRoomViewSettings RoomViewSettings
    * GMAssetCompiler.GMRoomPhysicsSettings RoomPhysicsSettings
    * Int32 CurrentInstanceID
    * Int32 CurrentTileID
    * Int32 CurrentLayerID
# GMAssetCompiler.GMRoom+<>c__DisplayClass150_0
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Guid id
# GMAssetCompiler.GMRoom+<>c__DisplayClass151_0
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 id
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
    * GMAssetCompiler.eScriptKind 
    * GMAssetCompiler.eScriptKind 
# GMAssetCompiler.GMScript
  ## Members
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * GMAssetCompiler.eScriptKind ()
    * Void (GMAssetCompiler.eScriptKind)
    * Int32 ()
    * Void (Int32)
    * Boolean ()
    * Void (Boolean)
    * . ()
    * Void (.)
    * Void (GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.List`1[System.String])
    * System.String ()
    * System.Guid ()
    * Void Dispose()
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
    * Boolean IsCompatibility
    * . Code
    * System.String Name
    * System.Guid GUID
    * System.String 
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
    * System.String ()
    * System.Guid ()
    * Void Dispose()
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
# GMAssetCompiler.GMSound+<>c__DisplayClass107_0
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String output
# GMAssetCompiler.GMSound+<>c
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * System.Diagnostics.DataReceivedEventHandler <>9__108_0
    * System.Diagnostics.DataReceivedEventHandler <>9__108_1
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
    * GMAssetCompiler.eGMSpriteType 
    * GMAssetCompiler.eGMSpriteType 
    * GMAssetCompiler.eGMSpriteType 
# .
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
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
# .
  ## Members
    * UInt32 ()
    * UInt32 ()
    * UInt32 ()
    * UInt32 ()
    * UInt32 ()
    * UInt32 ()
    * Byte[] ()
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
    * CollisionType get_ColCheck()
    * Int32 get_XOrig()
    * Int32 get_YOrig()
    * System.Collections.Generic.IList`1[System.String] get_Frames()
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
    * Single get_PlaybackSpeed()
    * Void set_PlaybackSpeed(Single)
    * Int32 get_PlaybackSpeedType()
    * Void set_PlaybackSpeedType(Int32)
    * Boolean get_SpriteNoExport()
    * Void set_SpriteNoExport(Boolean)
    * Int32 get_Index()
    * Void set_Index(Int32)
    * Void UpdateFileNames(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.List`1[System.String])
    * Void SetFromJson(GMAssetCompiler.GMAssets, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Byte[] GetSWFData()
    * Int32 GenerateSWFFrames(System.String, System.String, Single)
    * Int32 GenerateSWFShapes(System.String, System.String, Single)
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
    * System.String ()
    * System.Guid ()
    * Void Dispose()
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
    * CollisionType ColCheck
    * Int32 XOrig
    * Int32 YOrig
    * System.Collections.Generic.IList`1[System.String] Frames
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
    * Single PlaybackSpeed
    * Int32 PlaybackSpeedType
    * Boolean SpriteNoExport
    * Int32 Index
    * System.String Name
    * System.Guid GUID
    * Int32 SpineError_NoError
    * Int32 SpineError_NoAtlas
    * Int32 SpineError_InvalidAtlas
    * Int32 SpineError_InvalidJSON
    * Int32 SpineError_MultipleAtlasPages
    * Single SwfPrecisionMinValue
    * Single SwfPrecisionMaxValue
    * GMAssetCompiler.GMSprite+CollisionType
# GMAssetCompiler.GMSprite+CollisionType
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
    * CollisionType AXIS_ALIGNED_RECT
    * CollisionType PRECISE
    * CollisionType ROTATED_RECT
# GMAssetCompiler.GMMoment
  ## Members
    * Int32 get_Moment()
    * GMAssetCompiler.GMEvent get_Event()
    * GMAssetCompiler.SubTypeAndEvent get_Entry()
    * Void SetFromJson(GMAssetCompiler.GMAssets, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void UpdateEntry(GMAssetCompiler.GMAssets)
    * System.String ()
    * System.Guid ()
    * Void Dispose()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, GMAssetCompiler.GMTimeLine, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Int32 Moment
    * GMAssetCompiler.GMEvent Event
    * GMAssetCompiler.SubTypeAndEvent Entry
    * System.String Name
    * System.Guid GUID
# GMAssetCompiler.GMTimeLine
  ## Members
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMMoment] get_Moments()
    * System.Collections.Generic.IList`1[GMAssetCompiler.SubTypeAndEvent] get_Entries()
    * System.String get_SourceFileName()
    * Void set_SourceFileName(System.String)
    * Void SetFromJson(GMAssetCompiler.GMAssets, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void UpdateEntries(GMAssetCompiler.GMAssets)
    * Void UpdateEventCode(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.List`1[System.String])
    * System.String ()
    * System.Guid ()
    * Void Dispose()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.String)
    * Void .ctor(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * Void .ctor(GMAssetCompiler.GMAssets, System.IO.Stream)
    * System.Collections.Generic.IList`1[GMAssetCompiler.GMMoment] Moments
    * System.Collections.Generic.IList`1[GMAssetCompiler.SubTypeAndEvent] Entries
    * System.String SourceFileName
    * System.String Name
    * System.Guid GUID
    * System.String ResourceTreePath
# GMAssetCompiler.GMTimeLine+<>c__DisplayClass17_0
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String filename
# GMAssetCompiler.GMTrackViewFrameClock
  ## Members
    * Double get_FrameRate()
    * Void set_FrameRate(Double)
    * Void SetFromJson(System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * System.String ()
    * System.Guid ()
    * Void Dispose()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Double FrameRate
    * System.String Name
    * System.Guid GUID
# GMAssetCompiler.GMTrackView
  ## Members
    * System.String get_SourceFileName()
    * Void set_SourceFileName(System.String)
    * Int32 get_TrackCount()
    * Void set_TrackCount(Int32)
    * Void SetFromJson(GMAssetCompiler.GMAssets, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * System.String ()
    * System.Guid ()
    * Void Dispose()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.Dictionary`2[System.String,System.Object])
    * System.String SourceFileName
    * Int32 TrackCount
    * System.String Name
    * System.Guid GUID
    * System.String ResourceTreePath
    * GMAssetCompiler.GMTrackViewFrameClock Clock
# .
  ## Members
    * System.String ()
    * System.String ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Void (Int32)
    * System.String ()
    * Void (System.String)
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
# .
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
# .
  ## Members
    * System.Type ()
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
# .
  ## Members
    * System.Type ()
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
# .
  ## Members
    * System.Type ()
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
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Double 
    * Double 
    * Double 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Double 
    * Double 
    * Int32 
# .
  ## Members
    * System.Collections.IEnumerable (System.String[])
    * Boolean (System.String, System.String, System.String ByRef)
    * Boolean (System.String, System.String, System.String ByRef)
    * GMAssetCompiler.GMAssets (System.String)
    * UInt32 (System.String)
    * Int32 (Byte[])
    * UInt32 (Byte[], Int32)
    * UInt32 (System.Drawing.Bitmap)
    * Boolean (Byte[], Int32, System.String, UInt32)
    * Boolean (System.IO.Stream)
    * Boolean (System.IO.Stream)
    * Boolean (System.IO.Stream)
    * Void (GMAssetCompiler.GMAssets)
    * GMAssetCompiler.GMAssets (System.IO.Stream, System.String)
    * GMAssetCompiler.GMAssets (System.IO.Stream, System.String)
    * GMAssetCompiler.GMAssets (System.IO.Stream)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Byte[] 
# .+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(Int32)
    * System.String[] 
# .
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
    * . 
    * . 
    * . 
    * . 
    * . 
# .
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
    * . 
    * . 
    * . 
# .
  ## Members
    * System.String ()
    * System.String ()
    * System.String ()
    * . ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String Name
    * System.String Description
    * System.String Extension
    * . OutputType
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * Void (System.String)
    * System.Collections.Generic.Dictionary`2[System.String,System.String] ()
    * Void (System.Collections.Generic.Dictionary`2[System.String,System.String])
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String)
    * System.String Name
    * System.Collections.Generic.Dictionary`2[System.String,System.String] Entries
# .
  ## Members
    * System.Collections.Generic.Dictionary`2[System.String,.] ()
    * Void (System.Collections.Generic.Dictionary`2[System.String,.])
    * Void ()
    * . (System.String)
    * System.String (System.String, System.String, System.String)
    * Void (System.String, System.String, System.String)
    * System.String (System.String, System.String, System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String)
    * System.Collections.Generic.Dictionary`2[System.String,.] Sections
# .
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
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
# .
  ## Members
    * System.String ()
    * Double ()
    * . ()
    * System.String ()
    * Void (System.String)
    * Boolean ()
    * Void (Boolean)
    * Void (System.String, .)
    * Void (System.String, .)
    * . (System.String)
    * Void ()
    * Void (., System.String, Double)
    * Char ()
    * . (Char, .)
    * . ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(.)
    * System.String yyText
    * Double yyValue
    * . yyToken
    * System.String Text
    * Boolean CaseSensitive
# .
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(., System.String)
    * System.Collections.Generic.List`1[.] 
    * System.Collections.Generic.Dictionary`2[System.String,.] 
    * System.String 
    * . 
    * . 
    * System.String 
    * Double 
    * Boolean 
# .
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String)
    * Int32 
    * System.String 
    * System.Collections.Generic.List`1[.] 
    * Boolean 
# .
  ## Members
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Int32 ()
    * Void (Int32)
    * Boolean ()
    * Void (Boolean)
    * Int32 (System.Collections.Generic.List`1[.], Int32)
    * Int32 (System.Collections.Generic.List`1[.], Int32, Int32)
    * Void (System.Collections.Generic.List`1[.], Int32)
    * Int32 (System.Collections.Generic.List`1[.], Int32)
    * Void (System.Collections.Generic.List`1[.], System.IO.StreamWriter)
    * Void (System.IO.StreamWriter)
    * Void (System.Collections.Generic.IEnumerable`1[System.String], System.String, System.Collections.Generic.IEnumerable`1[System.String], GMAssetCompiler.GMAssets)
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
    * System.Collections.Generic.List`1[.] 
    * System.Collections.Generic.Dictionary`2[System.String,System.String] 
    * System.Collections.Generic.Dictionary`2[System.String,System.Int32] 
    * System.Collections.Generic.Dictionary`2[System.String,.] 
    * System.Collections.Generic.Dictionary`2[System.String,System.String] 
# .
  ## Members
    * GMAssetCompiler.eVM_Type ()
    * Void (GMAssetCompiler.eVM_Type)
    * . ()
    * Void (.)
    * System.Text.StringBuilder ()
    * Void (System.Text.StringBuilder)
    * System.Text.StringBuilder ()
    * Void (System.Text.StringBuilder)
    * System.Text.StringBuilder ()
    * Void (System.Text.StringBuilder)
    * System.String ()
    * Void (System.String)
    * UInt32 ()
    * Void (UInt32)
    * Int32 ()
    * Void (Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * GMAssetCompiler.eVM_Type Type
    * . VarTracking
    * System.Text.StringBuilder Expr
    * System.Text.StringBuilder Array1
    * System.Text.StringBuilder Array2
    * System.String Name
    * UInt32 Crc
    * Int32 StoreCount
    * System.Text.StringBuilder 
    * System.Text.StringBuilder 
    * System.Text.StringBuilder 
# .
  ## Members
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * . ()
    * Void (.)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * GMAssetCompiler.eKind ()
    * Void (GMAssetCompiler.eKind)
    * GMAssetCompiler.eKind ()
    * Void (GMAssetCompiler.eKind)
    * . ()
    * Void (.)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * System.String ()
    * Void (System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 ObjInd
    * Int32 ContextID
    * . ObjRefExpr
    * System.String VarInd
    * System.String ArrInd
    * System.String Name
    * System.String IndexName
    * Boolean Volatile
    * Boolean Local
    * GMAssetCompiler.eKind Kind
    * GMAssetCompiler.eKind PrevKind
    * . Var
    * Boolean SelfOrOther
    * Boolean BuiltIn
    * System.String BuiltInName
# .
  ## Members
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * Boolean ()
    * Void (Boolean)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Expression
    * Boolean VarArgsRef
# .
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
    * . 
    * . 
    * . 
# .
  ## Members
    * . ()
    * Void (.)
    * . ()
    * Void (.)
    * . ()
    * Void (.)
    * System.String ()
    * Void (System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(., ., .)
    * Void .ctor(System.String)
    * . Kind
    * . Assignment
    * . Load
    * System.String String
# .
  ## Members
    * System.String ()
    * Void (System.String)
    * GMAssetCompiler.eVM_Type ()
    * Void (GMAssetCompiler.eVM_Type)
    * . ()
    * Void (.)
    * Boolean ()
    * Void (Boolean)
    * Int32 ()
    * Void (Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String)
    * System.String Name
    * GMAssetCompiler.eVM_Type Type
    * . VarRef
    * Boolean Loaded
    * Int32 StoreCount
# .
  ## Members
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * System.Collections.Generic.List`1[System.String] ()
    * Void (System.Collections.Generic.List`1[System.String])
    * Int32 ()
    * System.Collections.Generic.Dictionary`2[System.String,.] ()
    * Void (System.Collections.Generic.Dictionary`2[System.String,.])
    * System.Collections.Generic.Dictionary`2[System.String,.] ()
    * Void (System.Collections.Generic.Dictionary`2[System.String,.])
    * Void (.)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(.)
    * System.Collections.Generic.List`1[.] StoreRefs
    * System.Collections.Generic.List`1[.] LoadRefs
    * System.Collections.Generic.List`1[System.String] ReturnsUsed
    * Int32 ID
    * System.Collections.Generic.Dictionary`2[System.String,.] DeclaredVars
    * System.Collections.Generic.Dictionary`2[System.String,.] UnDeclaredVars
    * Int32 
# .
  ## Members
    * System.String (GMAssetCompiler.eVM_Type)
    * System.String (GMAssetCompiler.eVM_Type)
    * System.String (.)
    * Void (System.String, System.Collections.Generic.List`1[System.String])
    * Void (GMAssetCompiler.GMAssets, .)
    * Void (System.Collections.Generic.List`1[System.String])
    * Int64 ()
    * Void (Int64)
    * System.Collections.Generic.Stack`1[System.Boolean] ()
    * Void (System.Collections.Generic.Stack`1[System.Boolean])
    * System.Collections.Generic.Stack`1[GMAssetCompiler.eVM_Type] ()
    * Void (System.Collections.Generic.Stack`1[GMAssetCompiler.eVM_Type])
    * System.Collections.Generic.Stack`1[.] ()
    * Void (System.Collections.Generic.Stack`1[.])
    * System.Collections.Generic.Stack`1[.] ()
    * Void (System.Collections.Generic.Stack`1[.])
    * System.Collections.Generic.Dictionary`2[System.Int32,System.Collections.Generic.List`1[System.Int64]] ()
    * Void (System.Collections.Generic.Dictionary`2[System.Int32,System.Collections.Generic.List`1[System.Int64]])
    * System.Collections.Generic.Dictionary`2[System.String,.] ()
    * Void (System.Collections.Generic.Dictionary`2[System.String,.])
    * System.Collections.Generic.Dictionary`2[System.String,System.Byte[]] ()
    * Void (System.Collections.Generic.Dictionary`2[System.String,System.Byte[]])
    * System.Collections.Generic.Dictionary`2[System.String,System.String] ()
    * Void (System.Collections.Generic.Dictionary`2[System.String,System.String])
    * System.String ()
    * Void (System.String)
    * System.Collections.Generic.List`1[System.String] ()
    * Void (System.Collections.Generic.List`1[System.String])
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * System.String ()
    * Void (System.String)
    * Boolean ()
    * Void (Boolean)
    * . ()
    * Void (.)
    * System.Collections.Generic.Stack`1[.] ()
    * Void (System.Collections.Generic.Stack`1[.])
    * System.Collections.Generic.Stack`1[System.Int32] ()
    * Void (System.Collections.Generic.Stack`1[System.Int32])
    * System.Collections.Generic.List`1[System.Int32] ()
    * Void (System.Collections.Generic.List`1[System.Int32])
    * Int32 ()
    * Void (Int32)
    * Boolean ()
    * Void (Boolean)
    * System.Collections.Generic.Dictionary`2[System.String,System.Double] ()
    * Void (System.Collections.Generic.Dictionary`2[System.String,System.Double])
    * System.Collections.Generic.Dictionary`2[System.String,System.Int64] ()
    * Void (System.Collections.Generic.Dictionary`2[System.String,System.Int64])
    * System.Collections.Generic.Dictionary`2[System.String,.] ()
    * Void (System.Collections.Generic.Dictionary`2[System.String,.])
    * System.Collections.Generic.List`1[System.Int32] ()
    * Void (System.Collections.Generic.List`1[System.Int32])
    * System.Text.StringBuilder ()
    * Void (System.Text.StringBuilder)
    * System.Collections.Generic.List`1[System.String] ()
    * Void (System.Collections.Generic.List`1[System.String])
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * System.Collections.Generic.Dictionary`2[System.Int32,System.String] ()
    * Void (System.Collections.Generic.Dictionary`2[System.Int32,System.String])
    * System.Collections.Generic.SortedDictionary`2[System.String,System.String] ()
    * Void (System.Collections.Generic.SortedDictionary`2[System.String,System.String])
    * System.Collections.Generic.SortedDictionary`2[System.String,System.String] ()
    * Void (System.Collections.Generic.SortedDictionary`2[System.String,System.String])
    * System.Collections.Generic.Dictionary`2[System.String,.] ()
    * Void (System.Collections.Generic.Dictionary`2[System.String,.])
    * Boolean ()
    * Void (Boolean)
    * . ()
    * Void (.)
    * . ()
    * Void (.)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Void (GMAssetCompiler.GMAssets, .)
    * Void (System.String, GMAssetCompiler.GMLToken)
    * Void (System.String, GMAssetCompiler.GMLToken)
    * GMAssetCompiler.GMLToken (GMAssetCompiler.GMLToken)
    * GMAssetCompiler.GMLToken (GMAssetCompiler.GMLToken)
    * GMAssetCompiler.GMLToken (GMAssetCompiler.GMLToken)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int64 OutputBase
    * System.Collections.Generic.Stack`1[System.Boolean] VariableExpressionStack
    * System.Collections.Generic.Stack`1[GMAssetCompiler.eVM_Type] TypeStack
    * System.Collections.Generic.Stack`1[.] LoopEnv
    * System.Collections.Generic.Stack`1[.] LoopEndEnv
    * System.Collections.Generic.Dictionary`2[System.Int32,System.Collections.Generic.List`1[System.Int64]] VarPatches
    * System.Collections.Generic.Dictionary`2[System.String,.] CPPVars
    * System.Collections.Generic.Dictionary`2[System.String,System.Byte[]] CPPStrings
    * System.Collections.Generic.Dictionary`2[System.String,System.String] CPPHashStrings
    * System.String FileName
    * System.Collections.Generic.List`1[System.String] UsedStrings
    * System.Collections.Generic.List`1[.] ScriptsUsed
    * Boolean IsScript
    * Boolean UsesArgs
    * Boolean UsesConcat
    * Boolean ForceInline
    * Boolean UsesConcatThisExpression
    * Int32 NumConcats
    * Int32 MaxNumConcats
    * System.String ReturnLabel
    * Boolean ReturnLabelUsed
    * . FuncSignature
    * System.Collections.Generic.Stack`1[.] VarTracking
    * System.Collections.Generic.Stack`1[System.Int32] ReturnStack
    * System.Collections.Generic.List`1[System.Int32] ReturnValueUsed
    * Int32 NumberReturnValues
    * Boolean GenerateArgumentCount
    * System.Collections.Generic.Dictionary`2[System.String,System.Double] ConstantDefs
    * System.Collections.Generic.Dictionary`2[System.String,System.Int64] ConstantLongDefs
    * System.Collections.Generic.Dictionary`2[System.String,.] LocalLegacyUsed
    * System.Collections.Generic.List`1[System.Int32] ArgumentStoredTo
    * System.Text.StringBuilder CompiledCode
    * System.Collections.Generic.List`1[System.String] Strings
    * Int32 LocalVarNumber
    * Int32 UniqueNumber
    * System.Collections.Generic.Dictionary`2[System.Int32,System.String] AllUniqueNumbers
    * System.Collections.Generic.SortedDictionary`2[System.String,System.String] GlobalVariables
    * System.Collections.Generic.SortedDictionary`2[System.String,System.String] InstanceVariables
    * System.Collections.Generic.Dictionary`2[System.String,.] LegacyUsed
    * Boolean UnityBuild
    * . Code
    * . VMB
    * Boolean ErrorFlag
    * Boolean ContinueIllegal
    * Int32 
    * Int32 
# .
  ## Members
    * . ()
    * Void (.)
    * . ()
    * Void (.)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Void (GMAssetCompiler.GMAssets, .)
    * Void (GMAssetCompiler.GMAssets, .)
    * Void (System.String, GMAssetCompiler.GMLToken)
    * Void (System.String, GMAssetCompiler.GMLToken)
    * GMAssetCompiler.GMLToken (GMAssetCompiler.GMLToken)
    * GMAssetCompiler.GMLToken (GMAssetCompiler.GMLToken)
    * GMAssetCompiler.GMLToken (GMAssetCompiler.GMLToken)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * . Code
    * . VMB
    * Boolean ErrorFlag
    * Boolean ContinueIllegal
    * Int32 
    * Int32 
    * System.Collections.Generic.Stack`1[GMAssetCompiler.eVM_Type] 
    * Int32 
    * System.Collections.Generic.Stack`1[System.Char] 
# .
  ## Members
    * . ()
    * Void (.)
    * Void (GMAssetCompiler.GMAssets, .)
    * Void (GMAssetCompiler.GMAssets, .)
    * . Code
# .
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
    * . 
    * . 
    * . 
    * . 
    * . 
# .
  ## Members
    * Boolean ()
    * Boolean ()
    * Boolean ()
    * Void ()
    * Int64 ()
    * Int64 ()
    * Void (Int64)
    * Int32 (Byte[], Int32, Int32)
    * Int64 (Int64, System.IO.SeekOrigin)
    * Void (Int64)
    * Void (Byte[], Int32, Int32)
    * Boolean get_CanRead()
    * Boolean get_CanSeek()
    * Boolean get_CanTimeout()
    * Boolean get_CanWrite()
    * Int64 get_Length()
    * Int64 get_Position()
    * Void set_Position(Int64)
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
    * Void Flush()
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
    * Int64 Seek(Int64, System.IO.SeekOrigin)
    * Void SetLength(Int64)
    * Int32 Read(Byte[], Int32, Int32)
    * Int32 ReadByte()
    * Void Write(Byte[], Int32, Int32)
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
# .
  ## Members
    * Void (System.String, GMAssetCompiler.GMLToken)
    * Void (GMAssetCompiler.GMAssets, ., System.IO.TextWriter)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String 
    * System.Collections.Generic.Dictionary`2[System.String,System.String] 
# .
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
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
# .
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
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
# .
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
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
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
    * GMAssetCompiler.eVM_Type eVMT_Delete
    * GMAssetCompiler.eVM_Type eVMT_Undefined
    * GMAssetCompiler.eVM_Type eVMT_UnsignedInt
# .
  ## Members
    * System.IO.MemoryStream ()
    * Void (System.IO.MemoryStream)
    * Int32 (Int32)
    * Int64 (Int32)
    * Single (Int32)
    * Double (Int32)
    * Void (Int32, Int32)
    * Void (Int32[])
    * Int32 (Int32, Int32)
    * Int32 (Int32, Int32)
    * Int32 (Int32, Int32, Int32)
    * Int32 (Int32, Int32)
    * Int32 (Int32)
    * Int32 (Int32)
    * Int32 (Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.MemoryStream Buffer
# .
  ## Members
    * . ()
    * Void (.)
    * System.String ()
    * Void (System.String)
    * Int64 ()
    * Void (Int64)
    * System.Collections.Generic.List`1[System.Int32] ()
    * Void (System.Collections.Generic.List`1[System.Int32])
    * Boolean ()
    * Void (Boolean)
    * Int32 ()
    * Void (Int32)
    * Void (Int64)
    * Void ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String, .)
    * . VMB
    * System.String Label
    * Int64 Address
    * System.Collections.Generic.List`1[System.Int32] Patches
    * Boolean Marked
    * Int32 BreakCount
# GMAssetCompiler.GML2VM
  ## Members
    * Int64 ()
    * Void (Int64)
    * System.Collections.Generic.Stack`1[System.Boolean] ()
    * Void (System.Collections.Generic.Stack`1[System.Boolean])
    * System.Collections.Generic.Stack`1[GMAssetCompiler.eVM_Type] ()
    * Void (System.Collections.Generic.Stack`1[GMAssetCompiler.eVM_Type])
    * System.Collections.Generic.Stack`1[.] ()
    * Void (System.Collections.Generic.Stack`1[.])
    * System.Collections.Generic.Stack`1[.] ()
    * Void (System.Collections.Generic.Stack`1[.])
    * System.Collections.Generic.List`1[System.Int32] ()
    * Void (System.Collections.Generic.List`1[System.Int32])
    * Int32 ()
    * Void (Int32)
    * System.Collections.Generic.List`1[System.String] ()
    * Void (System.Collections.Generic.List`1[System.String])
    * System.Collections.Generic.List`1[System.Int64] ()
    * Void (System.Collections.Generic.List`1[System.Int64])
    * System.Collections.Generic.Dictionary`2[System.Int32,System.Collections.Generic.List`1[GMAssetCompiler.GML2VM+]] ()
    * Void (System.Collections.Generic.Dictionary`2[System.Int32,System.Collections.Generic.List`1[GMAssetCompiler.GML2VM+]])
    * System.Collections.Generic.Dictionary`2[System.Int32,System.Collections.Generic.List`1[System.Int64]] ()
    * Void (System.Collections.Generic.Dictionary`2[System.Int32,System.Collections.Generic.List`1[System.Int64]])
    * System.Collections.Generic.List`1[System.Int32] ()
    * Void (System.Collections.Generic.List`1[System.Int32])
    * System.Collections.Generic.List`1[System.Int64] ()
    * Void (System.Collections.Generic.List`1[System.Int64])
    * Boolean (GMAssetCompiler.GMLToken, GMAssetCompiler.GMLToken)
    * Int32 (., Int32, System.IO.TextWriter)
    * Void (System.IO.TextWriter)
    * Void (GMAssetCompiler.GMAssets, .)
    * Void (GMAssetCompiler.GMAssets, .)
    * . ()
    * Void (.)
    * . ()
    * Void (.)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Void (System.String, GMAssetCompiler.GMLToken)
    * Void (System.String, GMAssetCompiler.GMLToken)
    * GMAssetCompiler.GMLToken (GMAssetCompiler.GMLToken)
    * GMAssetCompiler.GMLToken (GMAssetCompiler.GMLToken)
    * GMAssetCompiler.GMLToken (GMAssetCompiler.GMLToken)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int64 OutputBase
    * System.Collections.Generic.Stack`1[System.Boolean] VariableExpressionStack
    * System.Collections.Generic.Stack`1[GMAssetCompiler.eVM_Type] TypeStack
    * System.Collections.Generic.Stack`1[.] LoopEnv
    * System.Collections.Generic.Stack`1[.] LoopEndEnv
    * System.Collections.Generic.List`1[System.Int32] DebugInfo
    * Int32 LastDebugInfo
    * System.Collections.Generic.List`1[System.String] Strings
    * System.Collections.Generic.List`1[System.Int64] StringPatches
    * System.Collections.Generic.Dictionary`2[System.Int32,System.Collections.Generic.List`1[GMAssetCompiler.GML2VM+]] VarPatches
    * System.Collections.Generic.Dictionary`2[System.Int32,System.Collections.Generic.List`1[System.Int64]] FuncPatches
    * System.Collections.Generic.List`1[System.Int32] ObjectStringEntry
    * System.Collections.Generic.List`1[System.Int64] ObjectPatches
    * . Code
    * . VMB
    * Boolean ErrorFlag
    * Boolean ContinueIllegal
    * System.Collections.Generic.Dictionary`2[GMAssetCompiler.GML2VM+,System.Int32] 
    * GMAssetCompiler.GML2VM+EVariableType
    * GMAssetCompiler.GML2VM+
    * GMAssetCompiler.GML2VM+
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
# GMAssetCompiler.GML2VM+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor(Int64, EVariableType)
    * Int64 
    * EVariableType 
# GMAssetCompiler.GML2VM+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor(Int32, EVariableType, Int32)
    * Int32 
    * EVariableType 
    * Int32 
# GMAssetCompiler.GML2VM+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.List`1[System.String] 
# GMAssetCompiler.GML2VM+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * . 
    *  
# .
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
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
# .
  ## Members
    * System.String ()
    * System.String ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(., System.Collections.Generic.List`1[System.String])
    * System.String Decorated
    * System.String Undecorated
# .
  ## Members
    * System.String ()
    * System.String ()
    * Int64 ()
    * System.Collections.Generic.List`1[System.String] ()
    * System.Collections.Generic.List`1[.] ()
    * System.Collections.Generic.List`1[.] ()
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(., System.Collections.Generic.List`1[System.String])
    * System.String Decorated
    * System.String Undecorated
    * Int64 Offset
    * System.Collections.Generic.List`1[System.String] Args
    * System.Collections.Generic.List`1[.] Locals
    * System.Collections.Generic.List`1[.] InstanceVars
    * Int32 NumArguments
    * Int32 NumLocals
    * Int32 Flags
# .
  ## Members
    * . ()
    * Void (.)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * GMAssetCompiler.eScriptKind ()
    * Void (GMAssetCompiler.eScriptKind)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * GMAssetCompiler.GMLToken ()
    * Void (GMAssetCompiler.GMLToken)
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * System.Collections.Generic.Dictionary`2[System.String,System.String] ()
    * Void (System.Collections.Generic.Dictionary`2[System.String,System.String])
    * System.Collections.Generic.List`1[System.Int32] ()
    * Void (System.Collections.Generic.List`1[System.Int32])
    * System.Collections.Generic.List`1[GMAssetCompiler.GMLToken] ()
    * Void (System.Collections.Generic.List`1[GMAssetCompiler.GMLToken])
    * IntPtr ()
    * Void (IntPtr)
    * System.Collections.Generic.List`1[System.Collections.Generic.KeyValuePair`2[System.String,.]] ()
    * Void (System.Collections.Generic.List`1[System.Collections.Generic.KeyValuePair`2[System.String,.]])
    * Int32 ()
    * Void (Int32)
    * Int32 (Int32)
    * Void (GMAssetCompiler.GMLToken)
    * Void (GMAssetCompiler.GMLToken)
    * GMAssetCompiler.GMLToken (GMAssetCompiler.GMLToken)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMAssets, System.String, System.String, GMAssetCompiler.eScriptKind, ., Boolean, System.Collections.Generic.List`1[System.String])
    * . Type
    * System.String SourceFileName
    * System.String Name
    * System.String Code
    * GMAssetCompiler.eScriptKind Kind
    * Int32 NumArguments
    * Int32 ArgumentMask
    * GMAssetCompiler.GMLToken Token
    * System.Collections.Generic.List`1[.] Errors
    * System.Collections.Generic.Dictionary`2[System.String,System.String] LocalVars
    * System.Collections.Generic.List`1[System.Int32] NewLines
    * System.Collections.Generic.List`1[GMAssetCompiler.GMLToken] Pragmas
    * IntPtr pJavaScript
    * System.Collections.Generic.List`1[System.Collections.Generic.KeyValuePair`2[System.String,.]] SubFunctions
    * Int32 CodeIndex
    * System.Collections.Generic.Dictionary`2[System.String,System.Collections.Generic.List`1[System.Collections.Generic.KeyValuePair`2[.,GMAssetCompiler.GMLToken]]] 
    * System.Collections.Generic.Dictionary`2[System.String,System.Collections.Generic.List`1[System.Collections.Generic.KeyValuePair`2[.,GMAssetCompiler.GMLToken]]] 
    * Int32 
    * System.Collections.Generic.Dictionary`2[System.String,System.Int32] 
    * Int32 
    * System.Collections.Generic.Dictionary`2[System.String,System.Int32] 
    * Int32 
    * System.Collections.Generic.List`1[System.String] 
    * System.Collections.Generic.Dictionary`2[System.String,System.Collections.Generic.List`1[System.Collections.Generic.KeyValuePair`2[.,GMAssetCompiler.GMLToken]]] 
    * System.Collections.Generic.Dictionary`2[System.String,System.Collections.Generic.List`1[System.Collections.Generic.KeyValuePair`2[.,GMAssetCompiler.GMLToken]]] 
# .
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
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
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
    * GMAssetCompiler.eToken eConditional
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
    * GMAssetCompiler.eKind eInt64
# .
  ## Members
    * GMAssetCompiler.eKind ()
    * Void (GMAssetCompiler.eKind)
    * Boolean ()
    * Void (Boolean)
    * Double ()
    * Void (Double)
    * System.String ()
    * Void (System.String)
    * Int64 ()
    * Void (Int64)
    * System.String ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(Double)
    * Void .ctor(System.String)
    * Void .ctor(Int64)
    * Void .ctor(.)
    * GMAssetCompiler.eKind Kind
    * Boolean IsBool
    * Double ValueI
    * System.String ValueS
    * Int64 ValueL
# GMAssetCompiler.GMLToken
  ## Members
    * GMAssetCompiler.eToken ()
    * Void (GMAssetCompiler.eToken)
    * Int32 ()
    * Void (Int32)
    * System.String ()
    * Void (System.String)
    * GMAssetCompiler.eVM_Type ()
    * Void (GMAssetCompiler.eVM_Type)
    * GMAssetCompiler.eVM_Type ()
    * Void (GMAssetCompiler.eVM_Type)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * Int32 ()
    * Void (Int32)
    * . ()
    * Void (.)
    * System.Object ()
    * Void (System.Object)
    * System.Collections.Generic.List`1[GMAssetCompiler.GMLToken] ()
    * Void (System.Collections.Generic.List`1[GMAssetCompiler.GMLToken])
    * System.String ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.eToken, Int32, System.String)
    * Void .ctor(GMAssetCompiler.eToken, GMAssetCompiler.GMLToken, Int32)
    * Void .ctor(GMAssetCompiler.eToken, GMAssetCompiler.GMLToken, Int32, .)
    * Void .ctor(GMAssetCompiler.GMLToken)
    * GMAssetCompiler.eToken Token
    * Int32 Index
    * System.String Text
    * GMAssetCompiler.eVM_Type Type
    * GMAssetCompiler.eVM_Type OriginalType
    * System.String Script
    * System.String ScriptName
    * Int32 Id
    * . Value
    * System.Object Object
    * System.Collections.Generic.List`1[GMAssetCompiler.GMLToken] Children
    * System.Collections.Generic.Stack`1[System.String] 
    * System.Collections.Generic.Stack`1[System.String] 
# .
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
    * . 
    * . 
    * . 
# .
  ## Members
    * . ()
    * Void (.)
    * System.String ()
    * Void (System.String)
    * System.Collections.Generic.List`1[System.Object] ()
    * Void (System.Collections.Generic.List`1[System.Object])
    * GMAssetCompiler.GMLToken ()
    * Void (GMAssetCompiler.GMLToken)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(., System.String, GMAssetCompiler.GMLToken, System.Object[])
    * . Kind
    * System.String Error
    * System.Collections.Generic.List`1[System.Object] Params
    * GMAssetCompiler.GMLToken Token
# .
  ## Members
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Int32 ()
    * Void (Int32)
    * . ()
    * Void (.)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String JSName
    * Int32 Id
    * Int32 NumArgs7
    * Int32 NumArgs8
    * Boolean Pro
    * Boolean InstanceFirstParam
    * Boolean OtherSecondParam
    * Int32 Count
    * . Classification
# .
  ## Members
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * Int32 ()
    * Void (Int32)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
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
# .
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 
    * Int32 
    * Int32 
# GMAssetCompiler.GMLCompile
  ## Members
    * Boolean (Int32)
    * Boolean (Int32)
    * Boolean (Int32)
    * Void (System.String, GMAssetCompiler.eToken)
    * Void ()
    * Void (System.String, GMAssetCompiler.GMLToken)
    * Void (System.String, System.String, Int32)
    * Void (System.String, GMAssetCompiler.GMLToken)
    * Void ()
    * Int32 [](System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,]], System.String)
    * Void [](System.Collections.Generic.Dictionary`2[System.String,System.Int32], System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,]])
    * Void (System.Collections.Generic.Dictionary`2[System.String,System.Int32], System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMSprite]])
    * Int32 (System.Collections.Generic.IList`1[.], System.String)
    * Int32 (System.String, Int32, Int32, Int32)
    * Void (Int32, Int32 ByRef, Int32 ByRef, Int32 ByRef)
    * Int32 (System.String, System.String ByRef)
    * Int32 (GMAssetCompiler.GMAssets, System.Collections.Generic.Dictionary`2[System.String,System.Int32] ByRef, System.String)
    * Int32 (System.String, Boolean ByRef)
    * Boolean (System.String)
    * Boolean (System.String, Boolean)
    * Void (GMAssetCompiler.GMLToken ByRef)
    * Void (GMAssetCompiler.GMLToken ByRef)
    * Void (GMAssetCompiler.GMLToken ByRef)
    * Void (GMAssetCompiler.GMLToken ByRef)
    * Void (GMAssetCompiler.GMLToken ByRef)
    * Void (GMAssetCompiler.GMLToken ByRef)
    * Void (GMAssetCompiler.GMLToken ByRef)
    * Void (GMAssetCompiler.GMLToken ByRef)
    * Void (GMAssetCompiler.GMLToken ByRef)
    * GMAssetCompiler.GMLToken (GMAssetCompiler.GMLToken)
    * Boolean (GMAssetCompiler.GMAssets)
    * Void (System.String, System.String)
    * Void ()
    * GMAssetCompiler.GMLToken (GMAssetCompiler.GMAssets, System.String, System.String, System.Collections.Generic.List`1[.] ByRef, Boolean, Boolean)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.Dictionary`2[System.String,System.Double] 
    * System.Collections.Generic.Dictionary`2[System.String,System.Int32] 
    * System.Collections.Generic.Dictionary`2[System.String,.] 
    * System.Collections.Generic.Dictionary`2[System.String,.] 
    * System.Collections.Generic.Dictionary`2[System.String,.] 
    * System.Collections.Generic.Dictionary`2[System.String,.] 
    * System.Collections.Generic.Dictionary`2[System.String,.] 
    * System.Collections.Generic.Dictionary`2[System.String,.] 
    * System.Collections.Generic.Dictionary`2[System.String,.] 
    * System.Collections.Generic.Dictionary`2[System.String,System.Int32] 
    * System.Collections.Generic.Dictionary`2[System.Int32,System.Collections.Generic.Dictionary`2[System.Int32,System.Collections.Generic.Dictionary`2[System.Int32,System.Int32]]] 
    * System.Collections.Generic.List`1[GMAssetCompiler.GMLToken] 
    * .[] 
    * Int32 
    * System.Collections.Generic.Dictionary`2[System.String,System.String] 
    * System.Collections.Generic.Dictionary`2[System.String,System.Collections.Generic.Dictionary`2[System.String,System.Int32]] 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
# GMAssetCompiler.GMLCompile+<>c
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * System.Predicate`1[GMAssetCompiler.GMLToken] <>9__228_0
# GMAssetCompiler.HTML5Saver
  ## Members
    * GMAssetCompiler.GMAssets ()
    * System.String (System.String)
    * Void (GMAssetCompiler.GMAssets, System.String)
    * Void (System.String, System.String[], System.Collections.Generic.List`1[System.String])
    * System.String (Int32)
    * System.String (Int32, Int32)
    * System.String (System.String)
    * Void (GMAssetCompiler.GMAssets, System.IO.TextWriter)
    * Void (GMAssetCompiler.GMAssets, System.IO.TextWriter)
    * System.String (Int32)
    * System.String (Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * GMAssetCompiler.GMAssets Assets
    * System.Collections.Generic.Dictionary`2[System.String,.] 
    * System.Collections.Generic.List`1[System.String] 
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
# GMAssetCompiler.HTML5Saver+[]
  ## Members
    * Void Invoke(, System.IO.TextWriter, Int32)
    * System.IAsyncResult BeginInvoke(, System.IO.TextWriter, Int32, System.AsyncCallback, System.Object)
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
# GMAssetCompiler.HTML5Saver+
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
    *  
    *  
    *  
    *  
    *  
    *  
    *  
    *  
    *  
    *  
    *  
    *  
    *  
    *  
    *  
    *  
    *  
    *  
    *  
# GMAssetCompiler.HTML5Saver+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.TextWriter 
# GMAssetCompiler.HTML5Saver+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.TextWriter 
# GMAssetCompiler.HTML5Saver+<>c
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * WriteDelegateKVP`1 <>9__56_0
    * WriteDelegateKVP`1 <>9__57_0
    * System.Func`2[System.Byte[],System.Int32] <>9__59_0
    * WriteDelegateKVP`1 <>9__72_0
    * WriteDelegateKVP`1 <>9__83_0
    * System.Func`2[GMAssetCompiler.TexturePageEntry,System.Int32] <>9__85_0
# GMAssetCompiler.HTML5Saver+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.GMRoom]] 
# GMAssetCompiler.HTML5Saver+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.TextWriter 
# GMAssetCompiler.HTML5Saver+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.TextWriter 
# GMAssetCompiler.HTML5Saver+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.TextWriter 
    * System.Collections.Generic.List`1[System.String] 
# GMAssetCompiler.HTML5Saver+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.TextWriter 
# GMAssetCompiler.HTML5Saver+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.TextWriter 
# GMAssetCompiler.HTML5Saver+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.TextWriter 
# GMAssetCompiler.HTML5Saver+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String 
# GMAssetCompiler.HTML5Saver+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.TextWriter 
# GMAssetCompiler.HTML5Saver+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.TextWriter 
# GMAssetCompiler.HTML5Saver+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 
    *  
# GMAssetCompiler.HTML5Saver+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String 
    * Int32 
    * System.IO.TextWriter 
# GMAssetCompiler.HTML5Saver+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 
    *  
# GMAssetCompiler.HTML5Saver+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 
    *  
# GMAssetCompiler.HTML5Saver+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.TextWriter 
    * Boolean 
# GMAssetCompiler.HTML5Saver+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.TextWriter 
# .[]
  ## Members
    * Void Invoke(, System.IO.Stream, GMAssetCompiler.IFF)
    * System.IAsyncResult BeginInvoke(, System.IO.Stream, GMAssetCompiler.IFF, System.AsyncCallback, System.Object)
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
    * GMAssetCompiler.IFFChunkType 
    * GMAssetCompiler.IFFChunkType 
    * GMAssetCompiler.IFFChunkType 
    * GMAssetCompiler.IFFChunkType 
    * GMAssetCompiler.IFFChunkType 
# GMAssetCompiler.IIFFChunkHandler
  ## Members
    * GMAssetCompiler.IFFChunkType ()
    * Int32 ()
    * Int32 ()
    * System.String ()
    * Void (System.IO.Stream, GMAssetCompiler.IFF)
    * GMAssetCompiler.IFFChunkType Type
    * Int32 Align
    * Int32 Offset
    * System.String Name
# .[]
  ## Members
    * GMAssetCompiler.IFFChunkType ()
    * Int32 ()
    * Int32 ()
    * System.String ()
    * Void (System.IO.Stream, GMAssetCompiler.IFF)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * GMAssetCompiler.IFFChunkType Type
    * Int32 Align
    * Int32 Offset
    * System.String Name
# .
  ## Members
    * Int64 ()
    * System.Object ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(Int64, System.Object)
    * Int64 Site
    * System.Object Target
# .
  ## Members
    * System.String ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String)
    * System.String String
# GMAssetCompiler.IFF
  ## Members
    * System.Collections.Generic.List`1[.] ()
    * System.Collections.Generic.Dictionary`2[System.String,System.Int32] ()
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * System.Collections.Generic.Dictionary`2[System.String,System.UInt32] ()
    * Void (System.Collections.Generic.Dictionary`2[System.String,System.UInt32])
    * Int64 (System.Object)
    * Void (System.IO.Stream, System.Object, Int64)
    * . (System.String)
    * Void (System.IO.Stream, System.String)
    * Void (System.IO.Stream, System.Object)
    * Void [](System.String, .[], , GMAssetCompiler.IFFChunkType)
    * Void [](System.String, .[], , GMAssetCompiler.IFFChunkType, Int32)
    * Void [](System.String, .[], , GMAssetCompiler.IFFChunkType, Int32, Int32)
    * Void (System.IO.Stream, System.IO.TextWriter)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.List`1[.] Strings
    * System.Collections.Generic.Dictionary`2[System.String,System.Int32] StringCheck
    * System.Collections.Generic.List`1[.] ExternalFiles
    * System.Collections.Generic.Dictionary`2[System.String,System.UInt32] ExternalFileAttributes
    * System.Collections.Generic.List`1[GMAssetCompiler.IIFFChunkHandler] 
    * System.Collections.Generic.Dictionary`2[System.Object,System.Collections.Generic.List`1[.]] 
# GMAssetCompiler.IFF+<>c
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * System.Func`2[GMAssetCompiler.IIFFChunkHandler,GMAssetCompiler.IFFChunkType] <>9__27_0
# .
  ## Members
    * System.String ()
    * Void (System.String)
    * Void (GMAssetCompiler.GMAssets, System.String)
    * Void (GMAssetCompiler.GMExtension, GMAssetCompiler.GMExtensionInclude)
    * Boolean (GMAssetCompiler.GMAssets)
    * Void (System.Collections.Generic.IList`1[.], System.IO.Stream, GMAssetCompiler.IFF)
    * Void (System.Collections.Generic.IList`1[System.String], System.IO.Stream, GMAssetCompiler.IFF)
    * Void (System.Collections.Generic.IList`1[.], System.IO.Stream, GMAssetCompiler.IFF)
    * Void (System.Collections.Generic.IList`1[.], System.IO.Stream, GMAssetCompiler.IFF)
    * Void (System.Collections.Generic.IList`1[.], System.IO.Stream, GMAssetCompiler.IFF)
    * Void (System.Collections.Generic.IList`1[.], System.IO.Stream, GMAssetCompiler.IFF)
    * Void (System.Collections.Generic.IList`1[.], System.IO.Stream, GMAssetCompiler.IFF)
    * Void (GMAssetCompiler.GMAssets, System.IO.Stream)
    * Void (GMAssetCompiler.GMAssets, System.Collections.Generic.List`1[.])
    * Void (GMAssetCompiler.GMAssets, System.IO.Stream, System.Collections.Generic.List`1[.], System.Collections.Generic.Dictionary`2[System.String,System.UInt32])
    * Void [](System.Collections.Generic.IList`1[], System.IO.Stream, GMAssetCompiler.IFF, WriteDelegate`1)
    * Void [](System.Collections.Generic.IList`1[], System.IO.Stream, GMAssetCompiler.IFF, WriteDelegate`1)
    * Int32 (Int32)
    * Void (GMAssetCompiler.GMAssets, Int32 ByRef, Int32 ByRef)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String CPPDir
# GMAssetCompiler.WADSaver`1[TCode]
  ## Members
    * Void (GMAssetCompiler.GMExtension, GMAssetCompiler.GMExtensionInclude)
    * Boolean (GMAssetCompiler.GMAssets)
    * Void (System.Collections.Generic.IList`1[TCode], System.IO.Stream, GMAssetCompiler.IFF)
    * Void (System.Collections.Generic.IList`1[System.String], System.IO.Stream, GMAssetCompiler.IFF)
    * Void (System.Collections.Generic.IList`1[TCode], System.IO.Stream, GMAssetCompiler.IFF)
    * Void (System.Collections.Generic.IList`1[TCode], System.IO.Stream, GMAssetCompiler.IFF)
    * Void (System.Collections.Generic.IList`1[TCode], System.IO.Stream, GMAssetCompiler.IFF)
    * Void (System.Collections.Generic.IList`1[TCode], System.IO.Stream, GMAssetCompiler.IFF)
    * Void (System.Collections.Generic.IList`1[TCode], System.IO.Stream, GMAssetCompiler.IFF)
    * Void (GMAssetCompiler.GMAssets, System.IO.Stream)
    * Void (GMAssetCompiler.GMAssets, System.Collections.Generic.List`1[.])
    * Void (GMAssetCompiler.GMAssets, System.IO.Stream, System.Collections.Generic.List`1[.], System.Collections.Generic.Dictionary`2[System.String,System.UInt32])
    * Void [](System.Collections.Generic.IList`1[], System.IO.Stream, GMAssetCompiler.IFF, WriteDelegate`1)
    * Void [](System.Collections.Generic.IList`1[], System.IO.Stream, GMAssetCompiler.IFF, WriteDelegate`1)
    * Int32 (Int32)
    * Void (GMAssetCompiler.GMAssets, Int32 ByRef, Int32 ByRef)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * GMAssetCompiler.TexturePage 
    * System.Collections.Generic.SortedList`2[System.String,GMAssetCompiler.Wave] 
    * System.Collections.Generic.SortedList`2[System.String,GMAssetCompiler.Wave][] 
    * System.Collections.Generic.List`1[TCode] 
    * System.Collections.Generic.Dictionary`2[System.String,TCode] 
    * System.Collections.Generic.List`1[System.Int32] 
    * System.Collections.Generic.List`1[System.String] 
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
# GMAssetCompiler.WADSaver`1+<>c[TCode]
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * WriteDelegateKVP`1 <>9__85_0
    * Del_ParallelExec`2 <>9__86_0
    * Del_ParallelExec`2 <>9__88_0
    * WriteDelegateKVP`1 <>9__89_0
    * WriteDelegateKVP`1 <>9__90_0
    * WriteDelegateKVP`1 <>9__98_0
    * WriteDelegate`1 <>9__101_1
    * WriteDelegate`1 <>9__101_2
    * WriteDelegate`1 <>9__101_4
    * WriteDelegate`1 <>9__101_6
    * WriteDelegate`1 <>9__101_7
    * System.Func`2[GMAssetCompiler.TexturePageEntry,System.Int32] <>9__106_0
    * WriteDelegate`1 <>9__107_0
# GMAssetCompiler.WADSaver`1+[]
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * GMAssetCompiler.IFF 
    * System.Collections.Generic.SortedList`2[System.String,GMAssetCompiler.GMSound][] 
    * GMAssetCompiler.WADSaver`1[] 
# GMAssetCompiler.WADSaver`1+[]
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.List`1[System.Collections.Generic.List`1[GMAssetCompiler.TexturePageEntry]] 
    *  
# GMAssetCompiler.WADSaver`1+[]
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 
    * System.IO.Stream 
    * GMAssetCompiler.WADSaver`1[] 
# GMAssetCompiler.WADSaver`1+[]
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 
# GMAssetCompiler.WADSaver`1+[]
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.Stream 
# GMAssetCompiler.WADSaver`1+[]
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Double 
    * Double 
# GMAssetCompiler.WADSaver`1+[]
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * GMAssetCompiler.GMEvent 
    * GMAssetCompiler.WADSaver`1[] 
# GMAssetCompiler.WADSaver`1+[]
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.Stream 
    * GMAssetCompiler.WADSaver`1[] 
# GMAssetCompiler.WADSaver`1+[]
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * GMAssetCompiler.IFF 
    *  
# GMAssetCompiler.WADSaver`1+[]
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.List`1[System.Int32] 
# GMAssetCompiler.WADSaver`1+[]
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 
# GMAssetCompiler.WADSaver`1+[]
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.Stream 
    * Int32 
# .
  ## Members
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * GMAssetCompiler.eVM_Type ()
    * Void (GMAssetCompiler.eVM_Type)
    * System.Collections.Generic.List`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.eVM_Type]] ()
    * Void (System.Collections.Generic.List`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.eVM_Type]])
    * System.String ()
    * Void (System.String)
    * Boolean ()
    * Void (Boolean)
    * System.String ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String, System.String, System.String)
    * Void .ctor(System.String, System.String, GMAssetCompiler.eVM_Type)
    * System.String OrigGMLName
    * System.String GMLName
    * GMAssetCompiler.eVM_Type RetType
    * System.Collections.Generic.List`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.eVM_Type]] Args
    * System.String CPPName
    * Boolean VarArgs
# .
  ## Members
    * System.Collections.Generic.Stack`1[GMAssetCompiler.eVM_Type] ()
    * System.Collections.Generic.Dictionary`2[System.String,.] ()
    * Void (GMAssetCompiler.GMLToken)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.Stack`1[GMAssetCompiler.eVM_Type] TypeStack
    * System.Collections.Generic.Dictionary`2[System.String,.] GMLFunctions
# .
  ## Members
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(Int32, Int32)
    * Int32 Scaled
    * Int32 MipsToGenerate
# .
  ## Members
    * Int32 ()
    * Int32 ()
    * Byte[] ()
    * Void (IntPtr, IntPtr, UInt32)
    * System.Drawing.Bitmap (System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.IO.Stream)
    * Int32 Width
    * Int32 Height
    * Byte[] Pixels
    * Byte[] 
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
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
    * Int32 
    * Int64 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
    * Int32 
# .
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
    * . 
    * . 
    * . 
    * . 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
    * Int32 
    * Int64 
    * IntPtr 
    * Int32 
    * IntPtr 
    * Int32 
    * IntPtr 
    * Int32 
    * IntPtr 
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
    * IntPtr 
    * IntPtr 
    * IntPtr 
    * Int64 
    * IntPtr 
    * Int64 
    * Int32 
    * IntPtr 
    * Int32 
    * IntPtr 
    * Int32 
    * IntPtr 
    * Int32 
    * IntPtr 
    * Int32 
    * IntPtr 
    * Int32 
    * IntPtr 
# .
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
    * . 
    * . 
    * . 
    * . 
    * . 
# .
  ## Members
    * Void ()
    * Void ()
    * IntPtr (System.String, System.String, System.String)
    * IntPtr (IntPtr, Boolean)
    * Void (System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
# .
  ## Members
    * IntPtr (System.String, Int32, Int32, IntPtr, Int32, Int32, IntPtr)
    * IntPtr (IntPtr, IntPtr, Int32, Int32, Int32, System.String)
    * Boolean (IntPtr, Int32)
    * IntPtr (IntPtr, Int32, Int32, Int32, IntPtr)
    * IntPtr (Int32, Boolean, System.String)
    * Boolean (IntPtr)
    * Boolean (IntPtr)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 
    * Int32 
    * Int32 
    * Int32 
# .
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.GMExtension, GMAssetCompiler.GMExtensionInclude, .)
    * GMAssetCompiler.GMExtension 
    * GMAssetCompiler.GMExtensionInclude 
    * . 
# GMAssetCompiler.Program
  ## Members
    * Byte[] (Byte[])
    * Byte[] (System.String[])
    * Boolean (Byte[], Byte[])
    * Void (System.Collections.Generic.Dictionary`2[System.String,System.String], System.String, System.String)
    * Void (System.Collections.Generic.Dictionary`2[System.String,System.String], System.String, System.String)
    * Boolean (System.String)
    * System.Collections.Generic.Dictionary`2[System.String,System.Object] ()
    * Int64 (System.IO.Stream, System.IO.Stream)
    * System.String (Byte[])
    * Boolean (System.String, System.Collections.Generic.IList`1[System.String])
    * Boolean (System.String, System.String[])
    * System.String ()
    * System.Collections.Generic.List`1[] [,](System.Collections.Generic.IList`1[], Del_ParallelExec`2)
    * Byte[] (System.String)
    * System.String (Byte[])
    * System.String (System.String, System.String[])
    * Int32 (System.String, System.String)
    * Boolean ()
    * Void InitSession(System.String, System.Collections.Generic.IEnumerable`1[System.String])
    * Void QuitSession()
    * System.Collections.Generic.KeyValuePair`2[System.IO.MemoryStream,System.Int32] CompileExpression(System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String])
    * System.Collections.Generic.KeyValuePair`2[System.IO.MemoryStream,System.Int32] CompileStatement(System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String])
    * . ()
    * Void (.)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * . ()
    * Void (.)
    * Boolean ()
    * Void (Boolean)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * System.String ()
    * Void (System.String)
    * Boolean ()
    * Void (Boolean)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    *  ()
    * Void ()
    * Boolean ()
    * Void (Boolean)
    * System.String ()
    * Void (System.String)
    * Boolean ()
    * Void (Boolean)
    * Int32 ()
    * Void (Int32)
    * System.String ()
    * Void (System.String)
    * Int32 ()
    * Void (Int32)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * System.String ()
    * Void (System.String)
    * Single ()
    * Void (Single)
    * System.String ()
    * Void (System.String)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * Int32 ()
    * Void (Int32)
    * System.String ()
    * Void (System.String)
    * Int32 ()
    * Void (Int32)
    * Boolean ()
    * Void (Boolean)
    * System.Collections.Generic.List`1[System.String] ()
    * Void (System.Collections.Generic.List`1[System.String])
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * System.String (System.String, System.String, System.String)
    * System.Collections.Generic.IList`1[System.String] ()
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.Program+] ()
    * Void (System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.Program+])
    *  (System.String)
    * System.String (System.String)
    * System.String (.)
    * System.IO.TextWriter ()
    * Void (System.IO.TextWriter)
    * System.IO.TextWriter ()
    * Void (System.IO.TextWriter)
    * Void (System.String)
    * Void (System.String, System.String)
    * Void ()
    * Void (System.String, System.Collections.Generic.KeyValuePair`2[.,GMAssetCompiler.GMLToken])
    * Void ()
    * Void (GMAssetCompiler.GMAssets)
    * Double (System.DateTime)
    * Int32 (System.String, Int32, System.String ByRef)
    * Void (System.String, System.Object[])
    * Void (System.String, System.String, System.Object[])
    * Void (System.String, System.Object[])
    * System.String (System.String)
    * System.String (System.String)
    * System.String (System.String)
    * System.String (System.Collections.Generic.Dictionary`2[System.String,System.String], System.String)
    * Byte[] (System.String)
    * Boolean ()
    * Void (Boolean)
    * Int32 ()
    * Void (Int32)
    * Int64 ()
    * Void (Int64)
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * . ()
    * Void (.)
    * System.String ()
    * Void (System.String)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * System.String ()
    * Void (System.String)
    * Boolean ()
    * Void (Boolean)
    * Int32 ()
    * Void (Int32)
    * Boolean ()
    * Void (Boolean)
    * System.String ()
    * Void (System.String)
    * GMAssetCompiler.GMAssets ()
    * Void (GMAssetCompiler.GMAssets)
    * Boolean ()
    * Void (Boolean)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * Boolean ()
    * Void (Boolean)
    * System.String ()
    * Void (System.String)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * . ()
    * Void (.)
    * System.String ()
    * Void (System.String)
    * System.Globalization.CultureInfo ()
    * Void (System.Globalization.CultureInfo)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * GMAssetCompiler.eScriptKind ()
    * Void (GMAssetCompiler.eScriptKind)
    * System.String ()
    * Void (System.String)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * Boolean ()
    * Void (Boolean)
    * Int32 ()
    * Void (Int32)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * GMAssetCompiler.IFFSaver ()
    * Void (GMAssetCompiler.IFFSaver)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Boolean StudioData
    * Int32 MakerValue
    * Int64 TargetMask
    * System.Collections.Generic.List`1[.] ExtensionFunctionsUsed
    * . MachineType
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
    * Boolean PNGCrush
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
    * System.String PreProcessPathName
    * Boolean CompileToVM
    * System.String WorkingDirectory
    * Int32 Fellowship
    * Int32 Cabal
    * . License
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
    * Boolean NoBuiltIns
    * Boolean YYC_64_bit
    * System.String ZeusUserFolder
    * System.String ZeusInjectProject
    * Boolean ExperimentalVM2JS
    * Int32 NumProcessors
    * System.String BuildType
    * System.String ClangExeLocation
    * System.String ClangGMLIncludeLocation
    * GMAssetCompiler.IFFSaver IFFSaver
    * . LLVMSaver
    * System.String LLVMSourceDir
    * System.String MacHomeDir
    * . OptionsIniFile
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
    * System.String ExecutablePath
    * System.String YYDebugFile
    *  Architecture
    * Boolean BuildMetroProj
    * System.String MetroProjLocation
    * Boolean SteamProject
    * Int32 SteamAppId
    * System.String SteamLibrary
    * Int32 StudioEdition
    * Boolean Quiet
    * Boolean GenerateSWFImages
    * Boolean GenerateSWFShapes
    * System.String SWFFilename
    * Single SWFPrecision
    * System.String SpineFilename
    * Boolean GenerateSpineImage
    * Boolean GetSpineRootX
    * Boolean GetSpineRootY
    * System.String PS4SDKDir
    * System.String PSVitaSDKDir
    * System.String PS3SDKDir
    * System.String XboxOneManifestFile
    * Int32 DebuggerPort
    * System.String HostIP
    * Int32 HostPort
    * Boolean LicenseValidForBuild
    * System.Collections.Generic.List`1[System.String] LicenseExclusions
    * Boolean NoFullscreen
    * System.Collections.Generic.IList`1[System.String] ImagesToEmbed
    * System.Collections.Generic.Dictionary`2[System.String,GMAssetCompiler.Program+] TextureGroups
    * System.IO.TextWriter Out
    * System.IO.TextWriter Error
    * Boolean DebuggerSession
    * Boolean 
    * Boolean 
    * Boolean 
    * Boolean 
    * .[] 
    * Boolean 
    * Int32 
    * GMAssetCompiler.Program+
    * GMAssetCompiler.Program+
    * GMAssetCompiler.Program+Del_ParallelExec`2[R,T]
    * GMAssetCompiler.Program+
# GMAssetCompiler.Program+
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
    *  
    *  
    *  
    *  
    *  
    *  
# GMAssetCompiler.Program+
  ## Members
    * System.Collections.Generic.List`1[System.String] ()
    * Void (System.Collections.Generic.List`1[System.String])
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Int32 ()
    * Void (Int32)
    * Int64 ()
    * Void (Int64)
    *  ()
    * Void ()
    * System.String ()
    * Void (System.String)
    * Boolean ()
    * Void (Boolean)
    * Int32 ()
    * Void (Int32)
    * System.String ()
    * Void (System.String)
    * Int32 ()
    * Void (Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.Collections.Generic.List`1[System.String], Boolean, Int32, Boolean, Int64, System.String, System.String, Int32)
    * System.Collections.Generic.List`1[System.String] Resources
    * Boolean Scaled
    * Boolean RemoveSpace
    * Int32 Border
    * Int64 Targets
    *  Parent
    * System.String ParentName
    * Boolean UseFor3D
    * Int32 TexScale
    * System.String Name
    * Int32 MipsToGenerate
# GMAssetCompiler.Program+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
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
# GMAssetCompiler.Program+
  ## Members
    * Byte[] ()
    * Void (Byte[])
    * System.Collections.Generic.Dictionary`2[System.Int32,System.Collections.Generic.List`1[GMAssetCompiler.GML2VM+]] ()
    * Void (System.Collections.Generic.Dictionary`2[System.Int32,System.Collections.Generic.List`1[GMAssetCompiler.GML2VM+]])
    * System.Collections.Generic.Dictionary`2[System.Int32,System.Collections.Generic.List`1[System.Int64]] ()
    * Void (System.Collections.Generic.Dictionary`2[System.Int32,System.Collections.Generic.List`1[System.Int64]])
    * System.Collections.Generic.List`1[System.String] ()
    * Void (System.Collections.Generic.List`1[System.String])
    * System.Collections.Generic.List`1[System.Int64] ()
    * Void (System.Collections.Generic.List`1[System.Int64])
    * System.IO.StringWriter ()
    * Void (System.IO.StringWriter)
    * System.Text.StringBuilder ()
    * Void (System.Text.StringBuilder)
    * Int32 ()
    * Void (Int32)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * System.IO.MemoryStream ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Byte[] Code
    * System.Collections.Generic.Dictionary`2[System.Int32,System.Collections.Generic.List`1[GMAssetCompiler.GML2VM+]] VarPatches
    * System.Collections.Generic.Dictionary`2[System.Int32,System.Collections.Generic.List`1[System.Int64]] FuncPatches
    * System.Collections.Generic.List`1[System.String] Strings
    * System.Collections.Generic.List`1[System.Int64] StringPatches
    * System.IO.StringWriter Errors
    * System.Text.StringBuilder ErrorBuffer
    * Int32 NumErrors
    * System.String Name
# GMAssetCompiler.Program+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String 
    * System.String 
    * System.String 
# GMAssetCompiler.Program+<>c
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * System.Action`1[System.String] <>9__470_0
    * System.Action`1[System.String] <>9__470_1
    * System.Action`1[System.Int32] <>9__470_2
    * System.Action`1[System.String] <>9__470_3
    * System.Action`1[System.String] <>9__470_4
    * System.Action`1[System.String] <>9__470_5
    * System.Action`1[System.String] <>9__470_6
    * System.Action`1[System.Int32] <>9__470_7
    * System.Action`1[System.String] <>9__470_8
    * System.Action`1[System.String] <>9__470_9
    * System.Action`1[System.String] <>9__470_10
    * System.Action`1[System.String] <>9__470_11
    * System.Action`1[System.String] <>9__470_12
    * System.Action`1[System.String] <>9__470_13
    * System.Action`1[System.String] <>9__470_14
    * System.Action`1[System.String] <>9__470_15
    * System.Action`1[System.String] <>9__470_16
    * System.Action`1[System.Int32] <>9__470_17
    * System.Action`1[System.Int32] <>9__470_18
    * System.Action`1[System.Int32] <>9__470_19
    * System.Action`1[System.Int32] <>9__470_20
    * System.Action`1[System.String] <>9__470_21
    * System.Action`1[System.String] <>9__470_22
    * System.Action`1[System.String] <>9__470_23
    * System.Action`1[System.String] <>9__470_24
    * System.Action`1[System.String] <>9__470_25
    * System.Action`1[System.String] <>9__470_26
    * System.Action`1[System.String] <>9__470_27
    * System.Action`1[System.Boolean] <>9__470_28
    * System.Action`1[System.Boolean] <>9__470_29
    * System.Action`1[System.Boolean] <>9__470_30
    * System.Action`1[System.Boolean] <>9__470_31
    * System.Action`1[System.String] <>9__470_32
    * System.Action`1[System.String] <>9__470_33
    * System.Action`1[System.String] <>9__470_34
    * System.Action`1[System.String] <>9__470_35
    * System.Action`1[System.Int32] <>9__470_36
    * System.Action`1[System.String] <>9__470_37
    * System.Action`1[System.String] <>9__470_38
    * System.Action`1[System.String] <>9__470_39
    * System.Action`1[System.String] <>9__470_40
    * System.Action`1[System.String] <>9__470_41
    * System.Action`1[System.String] <>9__470_42
    * System.Action`1[System.String] <>9__470_43
    * System.Action`1[System.String] <>9__470_44
    * System.Action`1[System.String] <>9__470_45
    * System.Action`1[System.String] <>9__470_46
    * System.Action`1[System.String] <>9__470_47
    * System.Action`1[System.String] <>9__470_48
    * System.Action`1[System.String] <>9__470_49
    * System.Action`1[System.Int64] <>9__470_50
    * System.Action`1[System.String] <>9__470_51
    * System.Action`1[System.String] <>9__470_52
    * System.Action`1[System.String] <>9__470_53
    * System.Action`1[System.Int32] <>9__470_54
    * System.Action`1[System.String] <>9__470_55
    * System.Action`1[System.String] <>9__470_56
    * System.Action`1[System.String] <>9__470_57
    * System.Action`1[System.Int32] <>9__470_58
    * System.Action`1[System.String] <>9__470_59
    * System.Action`1[System.String] <>9__470_60
    * System.Action`1[System.String] <>9__470_61
    * System.Action`1[System.String] <>9__470_62
    * System.Action`1[System.String] <>9__470_63
    * System.Action`1[System.String] <>9__470_64
    * System.Action`1[System.String] <>9__470_65
    * System.Action`1[System.Boolean] <>9__470_66
    * System.Action`1[System.String] <>9__470_67
    * System.Action`1[System.String] <>9__470_68
    * System.Action`1[System.String] <>9__470_69
    * System.Action`1[System.String] <>9__470_70
    * System.Action`1[System.String] <>9__470_71
    * System.Action`1[System.String] <>9__470_72
    * System.Action`1[System.String] <>9__470_73
    * System.Action`1[System.String] <>9__470_74
    * System.Action`1[System.String] <>9__470_75
    * System.Action`1[System.String] <>9__470_76
    * System.Action`1[System.String] <>9__470_77
    * System.Action`1[System.String] <>9__470_78
    * System.Action`1[System.String] <>9__470_79
    * System.Action`1[System.String] <>9__470_80
    * System.Action`1[System.String] <>9__470_81
    * System.Func`2[System.Int32,System.Boolean] <>9__515_0
    * System.Diagnostics.DataReceivedEventHandler <>9__518_0
    * System.Diagnostics.DataReceivedEventHandler <>9__518_1
# GMAssetCompiler.Program+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.Dictionary`2[System.String,System.String] 
# GMAssetCompiler.Program+[,]
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.List`1[] 
    * Del_ParallelExec`2 
    * System.Collections.Generic.IList`1[] 
    * Int32 
    * System.Threading.WaitCallback 
# GMAssetCompiler.Program+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String 
# .
  ## Members
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.Object ()
    * Void (System.Object)
    * Boolean ()
    * Void (Boolean)
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
# .
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
    * . 
    * . 
    * . 
    * . 
# .
  ## Members
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * . ()
    * Void (.)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String)
    * Void .ctor(System.String, .)
    * System.String SourceFileName
    * System.String DestFileName
    * . Type
# GMAssetCompiler.IFFSaver
  ## Members
    * Void (GMAssetCompiler.GMAssets, System.String)
    * Void (GMAssetCompiler.GMAssets, System.String)
    * Void (GMAssetCompiler.GMAssets)
    * Void (GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.List`1[.])
    * Void (GMAssetCompiler.GMAssets)
    * Void (GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.List`1[.])
    * Void (GMAssetCompiler.GMAssets)
    * Void (GMAssetCompiler.GMAssets, System.String, System.Collections.Generic.List`1[.])
    * Void (System.Collections.Generic.IList`1[GMAssetCompiler.GML2VM], System.IO.Stream, GMAssetCompiler.IFF)
    * Void (System.Collections.Generic.IList`1[GMAssetCompiler.GML2VM], System.IO.Stream, GMAssetCompiler.IFF)
    * Void (System.Collections.Generic.IList`1[GMAssetCompiler.GML2VM], System.IO.Stream, GMAssetCompiler.IFF)
    * Void (System.Collections.Generic.IList`1[GMAssetCompiler.GML2VM], System.IO.Stream, GMAssetCompiler.IFF)
    * Void (System.Collections.Generic.IList`1[GMAssetCompiler.GML2VM], System.IO.Stream, GMAssetCompiler.IFF)
    * Void (System.Collections.Generic.IList`1[GMAssetCompiler.GML2VM], System.IO.Stream, GMAssetCompiler.IFF)
    * Void (System.Collections.Generic.IList`1[System.String], System.IO.Stream, GMAssetCompiler.IFF)
    * Void (GMAssetCompiler.GMExtension, GMAssetCompiler.GMExtensionInclude)
    * Boolean (GMAssetCompiler.GMAssets)
    * Void (GMAssetCompiler.GMAssets, System.IO.Stream)
    * Void (GMAssetCompiler.GMAssets, System.Collections.Generic.List`1[.])
    * Void (GMAssetCompiler.GMAssets, System.IO.Stream, System.Collections.Generic.List`1[.], System.Collections.Generic.Dictionary`2[System.String,System.UInt32])
    * Void [](System.Collections.Generic.IList`1[], System.IO.Stream, GMAssetCompiler.IFF, WriteDelegate`1)
    * Void [](System.Collections.Generic.IList`1[], System.IO.Stream, GMAssetCompiler.IFF, WriteDelegate`1)
    * Int32 (Int32)
    * Void (GMAssetCompiler.GMAssets, Int32 ByRef, Int32 ByRef)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
# GMAssetCompiler.IFFSaver+IFFSaverCodeEntry
  ## Members
    * GMAssetCompiler.GML2VM ()
    * Void (GMAssetCompiler.GML2VM)
    * Int64 ()
    * Void (Int64)
    * Int64 ()
    * Void (Int64)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * System.String ()
    * Void (System.String)
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * GMAssetCompiler.GML2VM Code
    * Int64 Offset
    * Int64 Length
    * Int32 NumLocals
    * Int32 NumArguments
    * Int32 Flags
    * System.String Name
# GMAssetCompiler.IFFSaver+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int64 
    * System.IO.Stream 
    * System.Collections.Generic.List`1[System.Byte[]] 
    * Int32 
    * Int32 
    * GMAssetCompiler.IFFSaver 
# GMAssetCompiler.IFFSaver+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.Stream 
# GMAssetCompiler.IFFSaver+<>c
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * WriteDelegate`1 <>9__21_0
    * WriteDelegate`1 <>9__22_0
# GMAssetCompiler.IFFSaver+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.IO.Stream 
# .
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
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
# .
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
    * . 
    * . 
    * . 
    * . 
    * . 
# .
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * .+
    * .+
    * .+
# .+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
# .+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
# .+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    *  
    *  
    * UInt32 
# .
  ## Members
    * . ()
    * Void (IntPtr, IntPtr, .)
    * Void (IntPtr, Int32, IntPtr, .)
    * Void (IntPtr, IntPtr, .)
    * Int32 (Int32, Int32, .)
    * Void (IntPtr, Int32, Int32, IntPtr, .)
    * Void (IntPtr, Int32, Int32, IntPtr, .)
    * Void (IntPtr, Int32, Int32, IntPtr, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
# .
  ## Members
    * Int16 (System.IO.Stream)
    * Int32 (System.IO.Stream)
    * Int64 (System.IO.Stream)
    * Boolean (System.IO.Stream)
    * System.String (System.IO.Stream)
    * System.Drawing.Image (System.IO.Stream)
    * System.Guid (System.IO.Stream)
    * Byte[] (System.IO.Stream)
    * System.IO.Stream (System.IO.Stream)
    * System.IO.Stream (System.IO.Stream)
    * Byte[] (System.IO.Stream)
    * Single (System.IO.Stream)
    * Double (System.IO.Stream)
    * Void (System.IO.Stream, Int32)
    * Void (System.IO.Stream, Int16)
    * Void (System.IO.Stream, System.Guid)
    * Void (System.IO.Stream, Int64)
    * Void (System.IO.Stream, Boolean)
    * Void (System.IO.Stream, System.String)
    * Int64 (System.IO.Stream)
    * Void (System.IO.Stream, Int64)
    * Void (System.IO.Stream, Int64)
    * Void (System.IO.Stream, System.String)
    * Void (System.IO.Stream, System.String)
    * Void (System.IO.Stream, Double)
    * Void (System.IO.Stream, Single)
    * Void (System.IO.Stream, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
# GMAssetCompiler.Texture
  ## Members
    * System.Drawing.Bitmap ()
    * Void (System.Drawing.Bitmap)
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * System.Collections.Generic.List`1[GMAssetCompiler.TexturePageEntry] ()
    * System.String ()
    * Void (System.String)
    * Byte[] ()
    * Void (Byte[])
    * Int32 ()
    * Void (Int32)
    * Void (Int32, Int32)
    * System.Drawing.Bitmap (System.Drawing.Bitmap, Int32, Int32)
    * Boolean (GMAssetCompiler.TexturePageEntry, Int32 ByRef, Int32 ByRef)
    * Void (IntPtr, IntPtr, UInt32)
    * Void ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(Byte[], Int32, Int32)
    * Void .ctor(Int32, Int32, Int32, Int32, Int32, Int32, Int32, Int32)
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
    * Int32 MipsToGenerate
    * . 
# .
  ## Members
    * System.String ()
    * Void (System.String)
    * System.Collections.Generic.List`1[GMAssetCompiler.Texture] ()
    * Void (System.Collections.Generic.List`1[GMAssetCompiler.Texture])
    * System.Collections.Generic.List`1[GMAssetCompiler.TexturePageEntry] ()
    * Void (System.Collections.Generic.List`1[GMAssetCompiler.TexturePageEntry])
    * Void (System.String)
    * Void (System.String, System.Collections.Generic.List`1[System.Collections.Generic.KeyValuePair`2[System.String,GMAssetCompiler.Texture]])
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
    * System.Collections.Generic.List`1[GMAssetCompiler.TexturePageEntry] ()
    * System.Collections.Generic.IEnumerable`1[GMAssetCompiler.Texture] ()
    * System.Collections.Generic.Dictionary`2[System.String,.] ()
    *  ()
    * Void ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Void ()
    * System.String (System.String)
    * Void ()
    * System.Drawing.Bitmap (System.Drawing.Bitmap, Int32, Int32)
    * GMAssetCompiler.TexturePageEntry (System.String, System.Drawing.Bitmap, Boolean, Boolean, Int32, System.String, System.String, System.String[])
    * GMAssetCompiler.TexturePageEntry (System.String, Boolean, Boolean, Int32, System.String, System.String, System.String[])
    * GMAssetCompiler.TexturePageEntry (System.Drawing.Bitmap, Boolean, Boolean, System.String, Int32, System.String)
    * Void ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(Int32, Int32, Int32, Int32, Int32, Int32)
    * System.Collections.Generic.List`1[GMAssetCompiler.TexturePageEntry] Entries
    * System.Collections.Generic.IEnumerable`1[GMAssetCompiler.Texture] Textures
    * System.Collections.Generic.Dictionary`2[System.String,.] TextureGroups
    *  CurrentGroup
    * Int32 MarginX
    * Int32 MarginY
    * Int32 GapX
    * Int32 GapY
    * Int32 TextureSizeWidth
    * Int32 TextureSizeHeight
# GMAssetCompiler.TexturePage+<>c
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * System.Func`2[GMAssetCompiler.TexturePageEntry,System.Boolean] <>9__51_0
    * System.Func`2[GMAssetCompiler.TexturePageEntry,System.String] <>9__51_1
    * System.Func`2[GMAssetCompiler.TexturePageEntry,System.Boolean] <>9__51_2
    * System.Func`2[GMAssetCompiler.TexturePageEntry,System.Int32] <>9__51_3
    * System.Func`2[GMAssetCompiler.TexturePageEntry,System.String] <>9__51_4
    * Del_ParallelExec`2 <>9__51_5
    * Del_ParallelExec`2 <>9__51_6
# GMAssetCompiler.TexturePageEntry
  ## Members
    * Int32 ()
    * Void (Int32)
    * UInt32 ()
    * Void (UInt32)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * GMAssetCompiler.TexturePageEntry ()
    * Void (GMAssetCompiler.TexturePageEntry)
    * System.Drawing.Bitmap ()
    * Void (System.Drawing.Bitmap)
    * System.String ()
    * Void (System.String)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * GMAssetCompiler.Texture ()
    * Void (GMAssetCompiler.Texture)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
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
    * Int32 
# .
  ## Members
    * Void (Void*, Byte, UInt32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 
    * Int32 
    * UInt32 
    * Int32 
    * UInt32 
    * UInt32 
    * Int32 
    * Int32 
# GMAssetCompiler.Wave
  ## Members
    * Boolean ()
    * Void (Boolean)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(GMAssetCompiler.IFF, Byte[], System.String, Boolean)
    * Boolean Valid
    * Byte[] 
    * System.String 
    * GMAssetCompiler.Wave+
# GMAssetCompiler.Wave+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * Int16 
    * Int16 
    * UInt32 
    * UInt32 
    * Int16 
    * Int16 
    * UInt32 
    * UInt32 
# .
  ## Members
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * System.String ()
    * . (Int32, Int32)
    * . (Int32, Int32)
    * Void ()
    * System.Drawing.Point (., Int32, Int32)
    * Void (System.Drawing.Graphics, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(Int32, Int32, Int32, Int32)
    * Int32 top
    * Int32 left
    * Int32 area
    * UInt64 
    * Boolean 
    * Boolean 
    * UInt16 
    * UInt16 
    * UInt16 
    * UInt16 
    * UInt16 
    * UInt16 
    * Int32 
    * System.Collections.Generic.List`1[.] 
# .
  ## Members
    * System.String ()
    * Void (System.String)
    * Void (System.String)
    * Void (System.String, System.Object[])
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Filename
    * System.IO.FileStream 
    * System.IO.StreamWriter 
# .
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
    * . 
    * . 
    * . 
    * . 
# .
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
    * . 
    * . 
# .
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
    * . 
    * . 
    * . 
    * . 
    * . 
# .
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
    * . 
    * . 
    * . 
    * . 
    * . 
# .
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
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
# .
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
    * . 
    * . 
# .
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String)
# .
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String)
# .
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
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
# .
  ## Members
    * Boolean (System.String)
    * Boolean (System.String, System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
# .
  ## Members
    * Int32[] (Spine.Skeleton)
    * Void (Spine.Skeleton, System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
# .+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(Single, Single, Single, Single)
    * Single 
    * Single 
    * Single 
    * Single 
# .+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(Single, Single, Single, Single)
    * Single 
    * Single 
    * Single 
    * Single 
# .
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
# GMAssetCompiler.Properties.Settings
  ## Members
    * GMAssetCompiler.Properties.Settings ()
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
# GMAssetCompiler.Output.LLVM_Switch
  ## Members
    * System.String ()
    * Void (System.String)
    * System.String ()
    * System.String ()
    * System.Collections.Generic.List`1[System.String] ()
    * Void (System.String, System.Object[])
    * Boolean (System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean (System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * Boolean (System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * System.String (System.String, System.String)
    * Boolean ()
    * Boolean ()
    * Boolean ()
    * Boolean (System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[.], GMAssetCompiler.GMAssets)
    * System.String ()
    * System.String (System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String SDKDir
    * System.String Name
    * System.String Extension
    * System.Collections.Generic.List`1[System.String] Archs
# GMAssetCompiler.Output.LLVM_Switch+<>c
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * System.Diagnostics.DataReceivedEventHandler <>9__17_0
    * System.Diagnostics.DataReceivedEventHandler <>9__17_1
# .
  ## Members
    * System.String ()
    * System.String ()
    * System.Collections.Generic.List`1[System.String] ()
    * Boolean (System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean (System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * Boolean (System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * System.String (System.String, System.String)
    * System.String ()
    * System.String (System.String)
    * Boolean ()
    * Boolean ()
    * Boolean ()
    * Boolean (System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[.], GMAssetCompiler.GMAssets)
    * System.String Name
    * System.String Extension
    * System.Collections.Generic.List`1[System.String] Archs
# GMAssetCompiler.Output.LLVM_tvOS
  ## Members
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * System.String ()
    * System.Collections.Generic.List`1[System.String] ()
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * Void (System.String, System.Object[])
    * Boolean (System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean (System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * System.String ()
    * System.String ()
    * System.String (System.String)
    * System.String ()
    * System.String ()
    * System.String ()
    * System.String ()
    * System.String (GMAssetCompiler.GMAssets)
    * System.String (GMAssetCompiler.GMAssets, System.String)
    * System.String ()
    * System.String ()
    * System.String (System.String ByRef)
    * System.String ()
    * Boolean (System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * Void (GMAssetCompiler.GMAssets)
    * Void (System.String, System.Uri, System.String)
    * Boolean (System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[.], GMAssetCompiler.GMAssets)
    * System.String (System.String, System.String)
    * Boolean ()
    * Boolean ()
    * Boolean ()
    * System.String ()
    * System.String (System.String)
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
    * System.Collections.Generic.List`1[.] SourceFiles
    * System.Collections.Generic.List`1[.] BundledFiles
    * System.Collections.Generic.List`1[.] ExtraFiles
    * System.Collections.Generic.List`1[.] FrameworkFiles
    * System.Collections.Generic.List`1[.] LocalFrameworkFiles
    * System.Collections.Generic.List`1[.] EmbeddedFrameworkFiles
    * System.Collections.Generic.List`1[.] LocalExtraFiles
    * System.Collections.Generic.List`1[.] FileGroups
# GMAssetCompiler.Output.LLVM_tvOS+<>c
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * System.Diagnostics.DataReceivedEventHandler <>9__77_0
    * System.Diagnostics.DataReceivedEventHandler <>9__77_1
# GMAssetCompiler.Output.LLVM_WindowsUAP
  ## Members
    * System.String ()
    * Void (System.String)
    * System.String ()
    * System.String ()
    * System.Collections.Generic.List`1[System.String] ()
    * Void (System.String, System.Object[])
    * Boolean (System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean (System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * Boolean (System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * System.String (System.String, System.String)
    * Boolean ()
    * Boolean ()
    * Boolean ()
    * Boolean (System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[.], GMAssetCompiler.GMAssets)
    * System.String ()
    * System.String (System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String SDKDir
    * System.String Name
    * System.String Extension
    * System.Collections.Generic.List`1[System.String] Archs
# GMAssetCompiler.Output.LLVM_WindowsUAP+<>c
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * System.Diagnostics.DataReceivedEventHandler <>9__17_0
    * System.Diagnostics.DataReceivedEventHandler <>9__17_1
# .
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
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
    * . 
# .
  ## Members
    * . ()
    * Void (.)
    * GMAssetCompiler.GMLToken (GMAssetCompiler.GMLToken)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(.)
    * . Code
    * System.Collections.Generic.Stack`1[System.Boolean] 
# .
  ## Members
    * GMAssetCompiler.GMLToken (GMAssetCompiler.GMLToken)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.Stack`1[System.Boolean] 
# .
  ## Members
    * GMAssetCompiler.GMLToken (GMAssetCompiler.GMLToken)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.Stack`1[System.Boolean] 
# .+
  ## Members
    * System.String ()
    * Void (System.String)
    * Int32 ()
    * Void (Int32)
    * System.String ()
    * Void (System.String)
    * Int32 ()
    * Void (Int32)
    * System.String ()
    * Void (System.String)
    * Int32 ()
    * Void (Int32)
    * System.String ()
    * Void (System.String)
    * Int32 ()
    * Void (Int32)
    * Int32 ()
    * Void (Int32)
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
# GMAssetCompiler.Output.LLVM_Android
  ## Members
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * System.String ()
    * System.Collections.Generic.List`1[System.String] ()
    * Void (System.String, System.Object[])
    * Boolean (System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean (System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * Boolean (System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * System.String (System.String, System.String)
    * Boolean ()
    * Boolean ()
    * Boolean ()
    * Boolean (System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[.], GMAssetCompiler.GMAssets)
    * System.String ()
    * System.String (System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String NDKDir
    * System.String ARMToolChain
    * System.String ARM64ToolChain
    * System.String MIPSToolChain
    * System.String X86ToolChain
    * System.String X86_64ToolChain
    * System.String PlatformDir
    * System.String Name
    * System.String Extension
    * System.Collections.Generic.List`1[System.String] Archs
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
# GMAssetCompiler.Output.LLVM_Android+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String 
    * System.Collections.Generic.List`1[System.Diagnostics.Process] 
    * GMAssetCompiler.Output.LLVM_Android 
# GMAssetCompiler.Output.LLVM_Android+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String 
    * System.String 
    *  
# GMAssetCompiler.Output.LLVM_Android+<>c
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * System.Diagnostics.DataReceivedEventHandler <>9__55_0
    * System.Diagnostics.DataReceivedEventHandler <>9__55_1
# .
  ## Members
    * UInt32 ()
    * Void (UInt32)
    * UInt32 ()
    * Void (UInt32)
    * UInt32 ()
    * Void (UInt32)
    * System.String ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * UInt32 ID0
    * UInt32 ID1
    * UInt32 ID2
    * UInt32 
    * UInt32 
    * UInt32 
# .
  ## Members
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * . ()
    * Void (.)
    * . ()
    * Void (.)
    * . ()
    * Void (.)
    * . ()
    * Void (.)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * Boolean ()
    * Void (Boolean)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String, System.String, System.String)
    * Void .ctor(System.String)
    * System.String Name
    * System.String DestName
    * . BuildID
    * . FileRefID
    * . GroupID
    * . SourceID
    * System.String MacLoc
    * System.String CompilerFlags
    * Boolean WeakRef
    * System.Collections.Generic.List`1[.] 
    * System.Collections.Generic.List`1[.] 
    * . 
# .
  ## Members
    * System.String ()
    * Void (System.String)
    * . ()
    * Void (.)
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String)
    * System.String DestPath
    * . GroupID
    * System.Collections.Generic.List`1[.] Files
# GMAssetCompiler.Output.LLVM_iOS
  ## Members
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * System.String ()
    * System.Collections.Generic.List`1[System.String] ()
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * Void (System.String, System.Object[])
    * Boolean (System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean (System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * System.String ()
    * System.String ()
    * System.String (System.String)
    * System.String ()
    * System.String ()
    * System.String ()
    * System.String ()
    * System.String (GMAssetCompiler.GMAssets)
    * System.String (GMAssetCompiler.GMAssets, System.String)
    * System.String ()
    * System.String ()
    * System.String (System.String ByRef)
    * System.String ()
    * Boolean (System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * Void (GMAssetCompiler.GMAssets)
    * Void (System.String, System.Uri, System.String)
    * Boolean (System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[.], GMAssetCompiler.GMAssets)
    * System.String (System.String, System.String)
    * Boolean ()
    * Boolean ()
    * Boolean ()
    * System.String ()
    * System.String (System.String)
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
    * System.Collections.Generic.List`1[.] SourceFiles
    * System.Collections.Generic.List`1[.] BundledFiles
    * System.Collections.Generic.List`1[.] ExtraFiles
    * System.Collections.Generic.List`1[.] FrameworkFiles
    * System.Collections.Generic.List`1[.] LocalFrameworkFiles
    * System.Collections.Generic.List`1[.] EmbeddedFrameworkFiles
    * System.Collections.Generic.List`1[.] LocalExtraFiles
    * System.Collections.Generic.List`1[.] FileGroups
# GMAssetCompiler.Output.LLVM_iOS+<>c
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * System.Diagnostics.DataReceivedEventHandler <>9__79_0
    * System.Diagnostics.DataReceivedEventHandler <>9__79_1
# .
  ## Members
    * System.String ()
    * Void (System.String)
    * System.String ()
    * System.String ()
    * System.Collections.Generic.List`1[System.String] ()
    * Void (System.String, System.Object[])
    * Boolean (System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean (System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * Boolean (System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * System.String (System.String, System.String)
    * Boolean ()
    * Boolean ()
    * Boolean ()
    * Boolean (System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[.], GMAssetCompiler.GMAssets)
    * System.String ()
    * System.String (System.String)
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
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * System.String ()
    * System.Collections.Generic.List`1[System.String] ()
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * System.Collections.Generic.List`1[.] ()
    * Void (System.Collections.Generic.List`1[.])
    * Void (System.String, System.Object[])
    * Boolean (System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean (System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * Boolean ()
    * Boolean ()
    * Boolean ()
    * System.String ()
    * System.String ()
    * System.String ()
    * System.String ()
    * System.String ()
    * System.String (GMAssetCompiler.GMAssets)
    * System.String (GMAssetCompiler.GMAssets, System.String)
    * System.String ()
    * System.String ()
    * System.String (System.String ByRef)
    * System.String ()
    * Boolean (System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * Void (GMAssetCompiler.GMAssets)
    * Void (System.String, System.Uri)
    * Boolean (System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[.], GMAssetCompiler.GMAssets)
    * System.String (System.String, System.String)
    * Boolean ()
    * Boolean ()
    * Boolean ()
    * System.String ()
    * System.String (System.String)
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
    * System.Collections.Generic.List`1[.] SourceFiles
    * System.Collections.Generic.List`1[.] BundledFiles
    * System.Collections.Generic.List`1[.] ExtraFiles
    * System.Collections.Generic.List`1[.] FrameworkFiles
    * System.Collections.Generic.List`1[.] LocalFrameworkFiles
    * System.Collections.Generic.List`1[.] LocalExtraFiles
    * System.Collections.Generic.List`1[.] FileGroups
# GMAssetCompiler.Output.LLVM_Mac+<>c
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * System.Diagnostics.DataReceivedEventHandler <>9__70_0
    * System.Diagnostics.DataReceivedEventHandler <>9__70_1
# GMAssetCompiler.Output.LLVM_PS3
  ## Members
    * System.String ()
    * Void (System.String)
    * System.String ()
    * System.String ()
    * System.Collections.Generic.List`1[System.String] ()
    * Void (System.String, System.Object[])
    * Boolean (System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean (System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * Boolean (System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * System.String (System.String, System.String)
    * Boolean ()
    * Boolean ()
    * Boolean ()
    * Boolean (System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[.], GMAssetCompiler.GMAssets)
    * System.String ()
    * System.String (System.String)
    * Boolean ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String SDKDir
    * System.String Name
    * System.String Extension
    * System.Collections.Generic.List`1[System.String] Archs
    * Boolean LowerCaseFileNames
# GMAssetCompiler.Output.LLVM_PS3+<>c
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * System.Diagnostics.DataReceivedEventHandler <>9__17_0
    * System.Diagnostics.DataReceivedEventHandler <>9__17_1
# GMAssetCompiler.Output.LLVM_PS4
  ## Members
    * System.String ()
    * Void (System.String)
    * System.String ()
    * System.String ()
    * System.Collections.Generic.List`1[System.String] ()
    * Void (System.String, System.Object[])
    * Boolean (System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean (System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * Boolean (System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * System.String (System.String, System.String)
    * Boolean ()
    * Boolean ()
    * Boolean ()
    * Boolean (System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[.], GMAssetCompiler.GMAssets)
    * System.String ()
    * System.String (System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String SDKDir
    * System.String Name
    * System.String Extension
    * System.Collections.Generic.List`1[System.String] Archs
# GMAssetCompiler.Output.LLVM_PS4+<>c
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * System.Diagnostics.DataReceivedEventHandler <>9__17_0
    * System.Diagnostics.DataReceivedEventHandler <>9__17_1
# GMAssetCompiler.Output.LLVM_PSVita
  ## Members
    * System.String ()
    * Void (System.String)
    * System.String ()
    * System.String ()
    * System.Collections.Generic.List`1[System.String] ()
    * Void (System.String, System.Object[])
    * Boolean (System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean (System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * Boolean (System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * System.String (System.String, System.String)
    * Boolean ()
    * Boolean ()
    * Boolean ()
    * Boolean (System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[.], GMAssetCompiler.GMAssets)
    * System.String ()
    * System.String (System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String SDKDir
    * System.String Name
    * System.String Extension
    * System.Collections.Generic.List`1[System.String] Archs
# GMAssetCompiler.Output.LLVM_PSVita+<>c
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * System.Diagnostics.DataReceivedEventHandler <>9__17_0
    * System.Diagnostics.DataReceivedEventHandler <>9__17_1
# GMAssetCompiler.Output.LLVM_Tizen
  ## Members
    * System.String ()
    * Void (System.String)
    * System.String ()
    * System.String ()
    * System.Collections.Generic.List`1[System.String] ()
    * Boolean (System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean (System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * Boolean (System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * System.String (System.String, System.String)
    * Boolean ()
    * Boolean ()
    * Boolean ()
    * Boolean (System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[.], GMAssetCompiler.GMAssets)
    * System.String ()
    * System.String (System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String TizenSDKDir
    * System.String Name
    * System.String Extension
    * System.Collections.Generic.List`1[System.String] Archs
# GMAssetCompiler.Output.LLVM_Tizen+<>c
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * System.Diagnostics.DataReceivedEventHandler <>9__14_0
    * System.Diagnostics.DataReceivedEventHandler <>9__14_1
# GMAssetCompiler.Output.LLVM_Windows
  ## Members
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * Void (System.String)
    * System.String ()
    * System.String ()
    * System.Collections.Generic.List`1[System.String] ()
    * System.String (System.String, System.Collections.Generic.Dictionary`2[System.String,System.String])
    * System.Collections.Generic.Dictionary`2[System.String,System.String] (System.String)
    * Boolean (System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean (System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * Boolean (System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * System.String (System.String, System.String)
    * Boolean ()
    * Boolean ()
    * Boolean ()
    * Boolean (System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[.], GMAssetCompiler.GMAssets)
    * System.String ()
    * System.String (System.String)
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
# GMAssetCompiler.Output.LLVM_Windows+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Text.StringBuilder 
# GMAssetCompiler.Output.LLVM_Windows+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String 
    * System.String 
    *  
# GMAssetCompiler.Output.LLVM_Windows+
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.List`1[System.Diagnostics.Process] 
    * GMAssetCompiler.Output.LLVM_Windows 
# GMAssetCompiler.Output.LLVM_Windows+<>c
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * System.Diagnostics.DataReceivedEventHandler <>9__38_1
    * System.Diagnostics.DataReceivedEventHandler <>9__38_2
    * System.Diagnostics.DataReceivedEventHandler <>9__43_0
    * System.Diagnostics.DataReceivedEventHandler <>9__43_1
# GMAssetCompiler.Output.LLVM_Windows8
  ## Members
    * System.String ()
    * Void (System.String)
    * System.String ()
    * System.String ()
    * System.Collections.Generic.List`1[System.String] ()
    * Void (System.String, System.Object[])
    * Boolean (System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean (System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * Boolean (System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * System.String (System.String, System.String)
    * Boolean ()
    * Boolean ()
    * Boolean ()
    * Boolean (System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[.], GMAssetCompiler.GMAssets)
    * System.String ()
    * System.String (System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String SDKDir
    * System.String Name
    * System.String Extension
    * System.Collections.Generic.List`1[System.String] Archs
# GMAssetCompiler.Output.LLVM_Windows8+<>c
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * System.Diagnostics.DataReceivedEventHandler <>9__17_0
    * System.Diagnostics.DataReceivedEventHandler <>9__17_1
# GMAssetCompiler.Output.LLVM_WindowsPhone
  ## Members
    * System.String ()
    * Void (System.String)
    * System.String ()
    * System.String ()
    * System.Collections.Generic.List`1[System.String] ()
    * Void (System.String, System.Object[])
    * Boolean (System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean (System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * Boolean (System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * System.String (System.String, System.String)
    * Boolean ()
    * Boolean ()
    * Boolean ()
    * Boolean (System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[.], GMAssetCompiler.GMAssets)
    * System.String ()
    * System.String (System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String SDKDir
    * System.String Name
    * System.String Extension
    * System.Collections.Generic.List`1[System.String] Archs
# GMAssetCompiler.Output.LLVM_WindowsPhone+<>c
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * System.Diagnostics.DataReceivedEventHandler <>9__17_0
    * System.Diagnostics.DataReceivedEventHandler <>9__17_1
# GMAssetCompiler.Output.LLVM_XBoxOne
  ## Members
    * System.String ()
    * Void (System.String)
    * System.String ()
    * System.String ()
    * System.Collections.Generic.List`1[System.String] ()
    * Void (System.String, System.Object[])
    * Boolean (System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[System.String], System.String)
    * Boolean (System.IO.MemoryStream, GMAssetCompiler.GMAssets, System.String, System.String)
    * Boolean (System.String, System.String, System.String, System.String, System.String, System.Collections.Generic.List`1[System.String])
    * System.String (System.String, System.String)
    * Boolean ()
    * Boolean ()
    * Boolean ()
    * Boolean (System.String, System.String, System.Collections.Generic.List`1[System.String], System.Collections.Generic.List`1[.], GMAssetCompiler.GMAssets)
    * System.String ()
    * System.String (System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String SDKDir
    * System.String Name
    * System.String Extension
    * System.Collections.Generic.List`1[System.String] Archs
# GMAssetCompiler.Output.LLVM_XBoxOne+<>c
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * System.Diagnostics.DataReceivedEventHandler <>9__17_0
    * System.Diagnostics.DataReceivedEventHandler <>9__17_1
# .
  ## Members
    * Int64 ()
    * Void (Int64)
    * Int64 ()
    * Void (Int64)
    * . ()
    * Void (.)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(., Int64, Int64)
    * Int64 InstructionOffset
    * Int64 TargetOffset
    * . Instruction
# GMAssetCompiler.Output.eVMCodeBlockType
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
    * GMAssetCompiler.Output.eVMCodeBlockType eVMCBT_Normal
    * GMAssetCompiler.Output.eVMCodeBlockType eVMCBT_IfBlock
    * GMAssetCompiler.Output.eVMCodeBlockType eVMCBT_ThenBlock
    * GMAssetCompiler.Output.eVMCodeBlockType eVMCBT_ElseBlock
    * GMAssetCompiler.Output.eVMCodeBlockType eVMCBT_WhileBlock
    * GMAssetCompiler.Output.eVMCodeBlockType eVMCBT_IfBreakBlock
    * GMAssetCompiler.Output.eVMCodeBlockType eVMCBT_DoWhileBlock
    * GMAssetCompiler.Output.eVMCodeBlockType eVMCBT_ForwardBlock
    * GMAssetCompiler.Output.eVMCodeBlockType eVMCBT_SwitchBlock
    * GMAssetCompiler.Output.eVMCodeBlockType eVMCBT_CaseBlock
    * GMAssetCompiler.Output.eVMCodeBlockType eVMCBT_RepeatBlock
    * GMAssetCompiler.Output.eVMCodeBlockType eVMCBT_AndBlock
# GMAssetCompiler.Output.VMCodeBlock
  ## Members
    * Int64 ()
    * Void (Int64)
    * Int64 ()
    * Void (Int64)
    * Int32 ()
    * GMAssetCompiler.Output.VMCodeBlock ()
    * Void (GMAssetCompiler.Output.VMCodeBlock)
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.VMCodeBlock] ()
    * Void (System.Collections.Generic.List`1[GMAssetCompiler.Output.VMCodeBlock])
    * GMAssetCompiler.Output.eVMCodeBlockType ()
    * Void (GMAssetCompiler.Output.eVMCodeBlockType)
    * Boolean ()
    * Void (Boolean)
    * . ()
    * Void (.)
    * Int32 ()
    * Void (Int32)
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.VMCodeBlock] (System.Collections.Generic.List`1[GMAssetCompiler.Output.VMCodeBlock], Int64, Int64, System.Collections.Generic.List`1[GMAssetCompiler.Output.VMCodeBlock] ByRef)
    * Void (Boolean ByRef)
    * Void (System.String, GMAssetCompiler.Output.VM2JS, System.Text.StringBuilder)
    * System.String ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(Int64, Int64)
    * Int64 OffsetStart
    * Int64 OffsetEnd
    * Int32 Index
    * GMAssetCompiler.Output.VMCodeBlock TargetCodeBlock
    * System.Collections.Generic.List`1[GMAssetCompiler.Output.VMCodeBlock] Children
    * GMAssetCompiler.Output.eVMCodeBlockType Type
    * Boolean InhibitDisasm
    * . VMB
    * Int32 ID
# GMAssetCompiler.Output.VM2JS
  ## Members
    * System.Collections.Generic.Stack`1[System.String] ()
    * Void (System.Collections.Generic.Stack`1[System.String])
    * GMAssetCompiler.Output.eVMCodeBlockType ()
    * Void (GMAssetCompiler.Output.eVMCodeBlockType)
    * Int32 (Int32, System.Text.StringBuilder)
    * Int32 (., Int32, System.Collections.Generic.List`1[.])
    * Void (., ., System.Text.StringBuilder)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Collections.Generic.Stack`1[System.String] VMStack
    * GMAssetCompiler.Output.eVMCodeBlockType Type
# GMAssetCompiler.Output.VM2JS+<>c
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * <>c <>9
    * System.Comparison`1[System.Int64] <>9__66_0
    * System.Comparison`1[GMAssetCompiler.Output.VMCodeBlock] <>9__66_1
# .
  ## Members
    * System.String ()
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * System.String Target
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
    * Int64 
    * Int64 
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * GMAssetCompiler.eShaderType ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eShaderType ShaderType
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Target
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * GMAssetCompiler.eShaderType ShaderType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * GMAssetCompiler.eShaderType ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eShaderType ShaderType
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * GMAssetCompiler.eShaderType ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eShaderType ShaderType
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * GMAssetCompiler.eShaderType ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eShaderType ShaderType
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * GMAssetCompiler.eShaderType ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * GMAssetCompiler.eShaderType ShaderType
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ()
    * System.String ()
    * . ()
    * System.String ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * Int32 ()
    * . ()
    * . ()
    * GMAssetCompiler.eShaderType ()
    * Boolean ()
    * UInt16 (Int32, Int32, Int32, Int32)
    * UInt32 (Int32, Int32, Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String Name
    * System.String Description
    * . OutputType
    * System.String Extension
    * Int32 TPageWidth
    * Int32 TPageHeight
    * Int32 TPageBorderTop
    * Int32 TPageBorderBottom
    * Int32 TPageBorderLeft
    * Int32 TPageBorderRight
    * . OpaqueTextureType
    * . AlphaTextureType
    * GMAssetCompiler.eShaderType ShaderType
    * Boolean LowerCaseFileNames
# .
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
# .+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
# .+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
# .+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
# .+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
# .+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
# .+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
# .+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
# .+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
# .+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
# .+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
# .
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
# .
  ## Members
    * Void ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
# .
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
# .+
  ## Members
    * System.String (Boolean)
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor(System.String)
    * System.String 
    * System.Version 
    * System.String 
    * System.String 
# SmartAssembly.MemoryManagement.MemoryManager
  ## Members
    * Void ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
# .
  ## Members
    * System.String ()
    * Int32 ()
    * System.String ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * System.String AppName
    * Int32 MajorVersion
    * System.String AppNameMinusVersion
# .
  ## Members
    * System.String ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
# .
  ## Members
    * System.String ()
    * System.String ()
    * System.Object (System.String, System.Object)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * System.String SubkeyApplication
    * System.String WowSubkeyApplication
# .
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
    * . 
    * . 
# .
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
# .
  ## Members
    * Byte[] (Byte[])
    * Byte[] (Byte[])
    * Byte[] (Byte[], Byte[], Byte[])
    * Byte[] (Byte[], Byte[], Byte[])
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * System.String 
# .+
  ## Members
    * Int32 (Byte[], Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(Byte[])
# .+
  ## Members
    * Int32 (Int32)
    * Void (Int32)
    * Int32 ()
    * Int32 ()
    * Void ()
    * Boolean ()
    * Int32 (Byte[], Int32, Int32)
    * Void ()
    * Void (Byte[], Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 AvailableBits
    * Int32 AvailableBytes
    * Boolean IsNeedingInput
# .+
  ## Members
    * Void (Int32)
    * Void (Int32, Int32)
    * Int32 (, Int32)
    * Void (Byte[], Int32, Int32)
    * Int32 ()
    * Int32 ()
    * Int32 (Byte[], Int32, Int32)
    * Void ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
# .+
  ## Members
    * Int32 ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(Byte[])
    *  
    *  
# .+
  ## Members
    * Boolean ()
    *  ()
    *  ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
# .+
  ## Members
    * Int64 ()
    * Void ()
    * Boolean ()
    * Boolean ()
    * Void (Byte[])
    * Int32 (Byte[])
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int64 TotalOut
    * Boolean IsFinished
    * Boolean IsNeedingInput
# .+
  ## Members
    * Int16 (Int32)
    * Void ()
    * Void (Int32)
    * Void ()
    * Void (Byte[], Int32, Int32, Boolean)
    * Void (Byte[], Int32, Int32, Boolean)
    * Boolean ()
    * Boolean (Int32)
    * Boolean (Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * .++
# .++
  ## Members
    * Void (Int32)
    * Void (Int16[], Byte[])
    * Void ()
    * Void ()
    * Int32 ()
    * Void ()
    * Void ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(, Int32, Int32, Int32)
    * Int16[] 
    * Byte[] 
    * Int32 
    * Int32 
# .+
  ## Members
    * Void ()
    * Boolean (Boolean, Boolean)
    * Void (Byte[])
    * Boolean ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
# .+
  ## Members
    * Void (Int32)
    * Void (Byte[], Int32, Int32)
    * Int32 ()
    * Void ()
    * Void (Int32, Int32)
    * Boolean ()
    * Int32 (Byte[], Int32, Int32)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 BitCount
    * Boolean IsFlushed
# .+
  ## Members
    * Void (Int32)
    * Void (Int32)
    * Int32 ()
    * Int32 ()
    * Boolean get_CanRead()
    * Boolean get_CanSeek()
    * Boolean get_CanWrite()
    * Void Flush()
    * System.Threading.Tasks.Task FlushAsync(System.Threading.CancellationToken)
    * Byte[] GetBuffer()
    * Boolean TryGetBuffer(System.ArraySegment`1[System.Byte] ByRef)
    * Int32 get_Capacity()
    * Void set_Capacity(Int32)
    * Int64 get_Length()
    * Int64 get_Position()
    * Void set_Position(Int64)
    * Int32 Read(Byte[], Int32, Int32)
    * System.Threading.Tasks.Task`1[System.Int32] ReadAsync(Byte[], Int32, Int32, System.Threading.CancellationToken)
    * Int32 ReadByte()
    * System.Threading.Tasks.Task CopyToAsync(System.IO.Stream, Int32, System.Threading.CancellationToken)
    * Int64 Seek(Int64, System.IO.SeekOrigin)
    * Void SetLength(Int64)
    * Byte[] ToArray()
    * Void Write(Byte[], Int32, Int32)
    * System.Threading.Tasks.Task WriteAsync(Byte[], Int32, Int32, System.Threading.CancellationToken)
    * Void WriteByte(Byte)
    * Void WriteTo(System.IO.Stream)
    * Boolean get_CanTimeout()
    * Int32 get_ReadTimeout()
    * Void set_ReadTimeout(Int32)
    * Int32 get_WriteTimeout()
    * Void set_WriteTimeout(Int32)
    * System.Threading.Tasks.Task CopyToAsync(System.IO.Stream)
    * System.Threading.Tasks.Task CopyToAsync(System.IO.Stream, Int32)
    * Void CopyTo(System.IO.Stream)
    * Void CopyTo(System.IO.Stream, Int32)
    * Void Close()
    * Void Dispose()
    * System.Threading.Tasks.Task FlushAsync()
    * System.IAsyncResult BeginRead(Byte[], Int32, Int32, System.AsyncCallback, System.Object)
    * Int32 EndRead(System.IAsyncResult)
    * System.Threading.Tasks.Task`1[System.Int32] ReadAsync(Byte[], Int32, Int32)
    * System.IAsyncResult BeginWrite(Byte[], Int32, Int32, System.AsyncCallback, System.Object)
    * Void EndWrite(System.IAsyncResult)
    * System.Threading.Tasks.Task WriteAsync(Byte[], Int32, Int32)
    * System.Object GetLifetimeService()
    * System.Object InitializeLifetimeService()
    * System.Runtime.Remoting.ObjRef CreateObjRef(System.Type)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(Byte[])
    * Boolean CanRead
    * Boolean CanSeek
    * Boolean CanWrite
    * Int32 Capacity
    * Int64 Length
    * Int64 Position
    * Boolean CanTimeout
    * Int32 ReadTimeout
    * Int32 WriteTimeout
# .
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
# .+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
# .+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
# .+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
# .+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
# .+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
# .+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
# .
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
# .
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
# .
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
# .
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
# .
  ## Members
    * Byte[] (Byte[], System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String 
# .
  ## Members
    * Void (.)
    * Void (.)
    * Void (.)
    * Void (System.EventHandler)
    * Void (System.EventHandler)
    * Void (System.Net.IWebProxy)
    * Void (.)
    * Void (.)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.Guid, System.Exception, System.Net.IWebProxy)
    * . FatalException
    * System.EventHandler DebuggerLaunched
    * . SendingReportFeedback
# .+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor(System.String)
    * System.String 
    * System.String 
    * System.String 
    * Int32 
# .+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor(System.String, System.String)
    * System.String 
    * System.String 
# .+
  ## Members
    * Boolean ()
    *  ()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Boolean IsEmpty
    *  Empty
    * System.String 
    *  
# .
  ## Members
    * Void (System.Net.IWebProxy)
    * Void (.)
    * Void (.)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * . SendingReportFeedback
# .+
  ## Members
    * Void (System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(., Byte[], ., )
    * Boolean 
# .+
  ## Members
    * Void (System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(.)
    * Boolean 
# .+
  ## Members
    * System.String ()
    * System.String ()
    * System.String ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String, System.String, System.String)
    * System.String BuildFriendlyNumber
    * System.String AppFriendlyName
    * System.String EmailAddress
    *  
# .
  ## Members
    * Boolean ()
    * System.Object ()
    * System.Type ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.Object, Boolean)
    * Void .ctor(System.Object, System.Type, Boolean)
    * Boolean FirstLevel
# .
  ## Members
    * System.Exception ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * System.Exception FatalException
# .
  ## Members
    * Void Invoke(System.Object, .)
    * System.IAsyncResult BeginInvoke(System.Object, ., System.AsyncCallback, System.Object)
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
# .
  ## Members
    * System.Exception ()
    * Boolean ()
    * Boolean ()
    * Boolean ()
    * Boolean ()
    * Boolean ()
    * Void (Boolean)
    * Void ()
    * Boolean (System.String)
    * Byte[] ()
    * Boolean ()
    * Void (System.String, System.String)
    * Void (System.String, System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * System.Exception Exception
    * Boolean CanDebug
    * Boolean CanSendReport
    * Boolean ShowContinueCheckbox
    * Boolean CanContinue
    * Boolean TryToContinue
# .
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
# .
  ## Members
    * System.Drawing.Bitmap (System.String)
    * System.Drawing.Icon (System.String)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
# .
  ## Members
    * System.Security.SecurityException ()
    * System.String ()
    * Boolean ()
    * Boolean ()
    * Void (Boolean)
    * Boolean ()
    * Void (Boolean)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.Security.SecurityException)
    * Void .ctor(System.Security.SecurityException, Boolean)
    * Void .ctor(System.String, Boolean)
    * System.Security.SecurityException SecurityException
    * System.String SecurityMessage
    * Boolean CanContinue
    * Boolean TryToContinue
    * Boolean ReportException
# .
  ## Members
    * Void Invoke(System.Object, .)
    * System.IAsyncResult BeginInvoke(System.Object, ., System.AsyncCallback, System.Object)
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
# .
  ## Members
    * . ()
    * Boolean ()
    * System.String ()
    * System.String ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * . Step
    * Boolean Failed
    * System.String ErrorMessage
    * System.String ReportID
# .
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
    * . 
    * . 
    * . 
    * . 
# SmartAssembly.SmartExceptionsCore.SmartStackFrame
  ## Members
    * Void GetObjectData(System.Runtime.Serialization.SerializationInfo, System.Runtime.Serialization.StreamingContext)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Int32 MethodID
    * System.Object[] Objects
    * Int32 ILOffset
    * Int32 ExceptionStackDepth
# .
  ## Members
    * Void (System.Exception)
    * Void (System.Exception, System.Object)
    * Void (System.Exception, System.Object, System.Object)
    * Void (System.Exception, System.Object, System.Object, System.Object)
    * Void (System.Exception, System.Object, System.Object, System.Object, System.Object)
    * Void (System.Exception, System.Object, System.Object, System.Object, System.Object, System.Object)
    * Void (System.Exception, System.Object, System.Object, System.Object, System.Object, System.Object, System.Object)
    * Void (System.Exception, System.Object, System.Object, System.Object, System.Object, System.Object, System.Object, System.Object)
    * Void (System.Exception, System.Object, System.Object, System.Object, System.Object, System.Object, System.Object, System.Object, System.Object)
    * Void (System.Exception, System.Object, System.Object, System.Object, System.Object, System.Object, System.Object, System.Object, System.Object, System.Object)
    * Void (System.Exception, System.Object, System.Object, System.Object, System.Object, System.Object, System.Object, System.Object, System.Object, System.Object, System.Object)
    * Void (System.Exception, System.Object[])
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String 
# .
  ## Members
    * Void Invoke(System.String)
    * System.IAsyncResult BeginInvoke(System.String, System.AsyncCallback, System.Object)
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
# .
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.String 
    * System.String 
    * System.String 
# .
  ## Members
    * Void (System.EventHandler)
    * Void (System.EventHandler)
    * Void (.)
    * Void (.)
    * Void (.)
    * Void (System.Exception, System.Object[])
    * Void (System.Exception)
    * System.Exception (System.Exception, System.Object[])
    * Void (System.Exception, System.Object[])
    * Void (System.Net.IWebProxy)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * System.EventHandler DebuggerLaunched
    * . SendingReportFeedback
    * System.String 
    * System.String 
# SmartAssembly.SmartExceptionsCore.UploadReportLoginService
  ## Members
    * System.String GetServerURL(System.String)
    * Void Discover()
    * System.Web.Services.Protocols.SoapProtocolVersion get_SoapVersion()
    * Void set_SoapVersion(System.Web.Services.Protocols.SoapProtocolVersion)
    * Boolean get_AllowAutoRedirect()
    * Void set_AllowAutoRedirect(Boolean)
    * System.Net.CookieContainer get_CookieContainer()
    * Void set_CookieContainer(System.Net.CookieContainer)
    * System.Security.Cryptography.X509Certificates.X509CertificateCollection get_ClientCertificates()
    * Boolean get_EnableDecompression()
    * Void set_EnableDecompression(Boolean)
    * System.String get_UserAgent()
    * Void set_UserAgent(System.String)
    * System.Net.IWebProxy get_Proxy()
    * Void set_Proxy(System.Net.IWebProxy)
    * Boolean get_UnsafeAuthenticatedConnectionSharing()
    * Void set_UnsafeAuthenticatedConnectionSharing(Boolean)
    * System.Net.ICredentials get_Credentials()
    * Void set_Credentials(System.Net.ICredentials)
    * Boolean get_UseDefaultCredentials()
    * Void set_UseDefaultCredentials(Boolean)
    * System.String get_ConnectionGroupName()
    * Void set_ConnectionGroupName(System.String)
    * Boolean get_PreAuthenticate()
    * Void set_PreAuthenticate(Boolean)
    * System.String get_Url()
    * Void set_Url(System.String)
    * System.Text.Encoding get_RequestEncoding()
    * Void set_RequestEncoding(System.Text.Encoding)
    * Int32 get_Timeout()
    * Void set_Timeout(Int32)
    * Void Abort()
    * Void add_Disposed(System.EventHandler)
    * Void remove_Disposed(System.EventHandler)
    * System.ComponentModel.ISite get_Site()
    * Void set_Site(System.ComponentModel.ISite)
    * Void Dispose()
    * System.ComponentModel.IContainer get_Container()
    * System.String ToString()
    * System.Object GetLifetimeService()
    * System.Object InitializeLifetimeService()
    * System.Runtime.Remoting.ObjRef CreateObjRef(System.Type)
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Web.Services.Protocols.SoapProtocolVersion SoapVersion
    * Boolean AllowAutoRedirect
    * System.Net.CookieContainer CookieContainer
    * System.Security.Cryptography.X509Certificates.X509CertificateCollection ClientCertificates
    * Boolean EnableDecompression
    * System.String UserAgent
    * System.Net.IWebProxy Proxy
    * Boolean UnsafeAuthenticatedConnectionSharing
    * System.Net.ICredentials Credentials
    * Boolean UseDefaultCredentials
    * System.String ConnectionGroupName
    * Boolean PreAuthenticate
    * System.String Url
    * System.Text.Encoding RequestEncoding
    * Int32 Timeout
    * System.ComponentModel.ISite Site
    * System.ComponentModel.IContainer Container
    * System.EventHandler Disposed
# SmartAssembly.SmartExceptionsCore.ReportingService
  ## Members
    * System.String UploadReport2(System.String, Byte[], System.String, System.String, System.String)
    * Void Discover()
    * System.Web.Services.Protocols.SoapProtocolVersion get_SoapVersion()
    * Void set_SoapVersion(System.Web.Services.Protocols.SoapProtocolVersion)
    * Boolean get_AllowAutoRedirect()
    * Void set_AllowAutoRedirect(Boolean)
    * System.Net.CookieContainer get_CookieContainer()
    * Void set_CookieContainer(System.Net.CookieContainer)
    * System.Security.Cryptography.X509Certificates.X509CertificateCollection get_ClientCertificates()
    * Boolean get_EnableDecompression()
    * Void set_EnableDecompression(Boolean)
    * System.String get_UserAgent()
    * Void set_UserAgent(System.String)
    * System.Net.IWebProxy get_Proxy()
    * Void set_Proxy(System.Net.IWebProxy)
    * Boolean get_UnsafeAuthenticatedConnectionSharing()
    * Void set_UnsafeAuthenticatedConnectionSharing(Boolean)
    * System.Net.ICredentials get_Credentials()
    * Void set_Credentials(System.Net.ICredentials)
    * Boolean get_UseDefaultCredentials()
    * Void set_UseDefaultCredentials(Boolean)
    * System.String get_ConnectionGroupName()
    * Void set_ConnectionGroupName(System.String)
    * Boolean get_PreAuthenticate()
    * Void set_PreAuthenticate(Boolean)
    * System.String get_Url()
    * Void set_Url(System.String)
    * System.Text.Encoding get_RequestEncoding()
    * Void set_RequestEncoding(System.Text.Encoding)
    * Int32 get_Timeout()
    * Void set_Timeout(Int32)
    * Void Abort()
    * Void add_Disposed(System.EventHandler)
    * Void remove_Disposed(System.EventHandler)
    * System.ComponentModel.ISite get_Site()
    * Void set_Site(System.ComponentModel.ISite)
    * Void Dispose()
    * System.ComponentModel.IContainer get_Container()
    * System.String ToString()
    * System.Object GetLifetimeService()
    * System.Object InitializeLifetimeService()
    * System.Runtime.Remoting.ObjRef CreateObjRef(System.Type)
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String)
    * System.Web.Services.Protocols.SoapProtocolVersion SoapVersion
    * Boolean AllowAutoRedirect
    * System.Net.CookieContainer CookieContainer
    * System.Security.Cryptography.X509Certificates.X509CertificateCollection ClientCertificates
    * Boolean EnableDecompression
    * System.String UserAgent
    * System.Net.IWebProxy Proxy
    * Boolean UnsafeAuthenticatedConnectionSharing
    * System.Net.ICredentials Credentials
    * Boolean UseDefaultCredentials
    * System.String ConnectionGroupName
    * Boolean PreAuthenticate
    * System.String Url
    * System.Text.Encoding RequestEncoding
    * Int32 Timeout
    * System.ComponentModel.ISite Site
    * System.ComponentModel.IContainer Container
    * System.EventHandler Disposed
# .
  ## Members
    * Void (System.Net.IWebProxy)
    * Void (.)
    * Void (Byte[], System.String, System.String, System.String, .)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.String)
# .
  ## Members
    * System.Drawing.Icon ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * .+
# .+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Void .ctor(System.Drawing.Rectangle)
    * Int32 
    * Int32 
    * Int32 
    * Int32 
# .+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * Int32 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt32 
    * System.String 
    * UInt16 
    * UInt16 
    * UInt16 
    * Byte 
# .+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
    * UInt16 
    * UInt32 
    * IntPtr 
    * IntPtr 
    * IntPtr 
    * UInt32 
    * UInt32 
    * UInt32 
    * UInt16 
    * UInt16 
# .
  ## Members
    * Void ()
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor(System.Xml.XmlWriter, System.String)
# .
  ## Members
    * Void set_FlatStyle(System.Windows.Forms.FlatStyle)
    * Void set_Image(System.Drawing.Image)
    * Void set_ImageIndex(Int32)
    * Void set_ImageAlign(System.Drawing.ContentAlignment)
    * Void set_TabStop(Boolean)
    * Void set_UseMnemonic(Boolean)
    * Boolean get_AutoSize()
    * Void set_AutoSize(Boolean)
    * Void add_AutoSizeChanged(System.EventHandler)
    * Void remove_AutoSizeChanged(System.EventHandler)
    * Boolean get_AutoEllipsis()
    * Void set_AutoEllipsis(Boolean)
    * System.Drawing.Image get_BackgroundImage()
    * Void set_BackgroundImage(System.Drawing.Image)
    * Void add_BackgroundImageChanged(System.EventHandler)
    * Void remove_BackgroundImageChanged(System.EventHandler)
    * System.Windows.Forms.ImageLayout get_BackgroundImageLayout()
    * Void set_BackgroundImageLayout(System.Windows.Forms.ImageLayout)
    * Void add_BackgroundImageLayoutChanged(System.EventHandler)
    * Void remove_BackgroundImageLayoutChanged(System.EventHandler)
    * System.Windows.Forms.BorderStyle get_BorderStyle()
    * Void set_BorderStyle(System.Windows.Forms.BorderStyle)
    * System.Windows.Forms.FlatStyle get_FlatStyle()
    * System.Drawing.Image get_Image()
    * Int32 get_ImageIndex()
    * System.String get_ImageKey()
    * Void set_ImageKey(System.String)
    * System.Windows.Forms.ImageList get_ImageList()
    * Void set_ImageList(System.Windows.Forms.ImageList)
    * System.Drawing.ContentAlignment get_ImageAlign()
    * System.Windows.Forms.ImeMode get_ImeMode()
    * Void set_ImeMode(System.Windows.Forms.ImeMode)
    * Void add_ImeModeChanged(System.EventHandler)
    * Void remove_ImeModeChanged(System.EventHandler)
    * Void add_KeyUp(System.Windows.Forms.KeyEventHandler)
    * Void remove_KeyUp(System.Windows.Forms.KeyEventHandler)
    * Void add_KeyDown(System.Windows.Forms.KeyEventHandler)
    * Void remove_KeyDown(System.Windows.Forms.KeyEventHandler)
    * Void add_KeyPress(System.Windows.Forms.KeyPressEventHandler)
    * Void remove_KeyPress(System.Windows.Forms.KeyPressEventHandler)
    * Int32 get_PreferredHeight()
    * Int32 get_PreferredWidth()
    * Boolean get_TabStop()
    * Void add_TabStopChanged(System.EventHandler)
    * Void remove_TabStopChanged(System.EventHandler)
    * System.Drawing.ContentAlignment get_TextAlign()
    * Void set_TextAlign(System.Drawing.ContentAlignment)
    * System.String get_Text()
    * Void set_Text(System.String)
    * Void add_TextAlignChanged(System.EventHandler)
    * Void remove_TextAlignChanged(System.EventHandler)
    * Boolean get_UseCompatibleTextRendering()
    * Void set_UseCompatibleTextRendering(Boolean)
    * Boolean get_UseMnemonic()
    * System.Drawing.Size GetPreferredSize(System.Drawing.Size)
    * System.String ToString()
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
    * System.Drawing.Color get_BackColor()
    * Void set_BackColor(System.Drawing.Color)
    * Void add_BackColorChanged(System.EventHandler)
    * Void remove_BackColorChanged(System.EventHandler)
    * Void add_BackgroundImageChanged(System.EventHandler)
    * Void remove_BackgroundImageChanged(System.EventHandler)
    * Void add_BackgroundImageLayoutChanged(System.EventHandler)
    * Void remove_BackgroundImageLayoutChanged(System.EventHandler)
    * Void ResetBindings()
    * System.Windows.Forms.BindingContext get_BindingContext()
    * Void set_BindingContext(System.Windows.Forms.BindingContext)
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
    * System.Drawing.Rectangle get_DisplayRectangle()
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
    * System.Drawing.Size get_MaximumSize()
    * Void set_MaximumSize(System.Drawing.Size)
    * System.Drawing.Size get_MinimumSize()
    * Void set_MinimumSize(System.Drawing.Size)
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
    * Void .ctor()
    * Boolean AutoSize
    * Boolean AutoEllipsis
    * System.Drawing.Image BackgroundImage
    * System.Windows.Forms.ImageLayout BackgroundImageLayout
    * System.Windows.Forms.BorderStyle BorderStyle
    * System.Windows.Forms.FlatStyle FlatStyle
    * System.Drawing.Image Image
    * Int32 ImageIndex
    * System.String ImageKey
    * System.Windows.Forms.ImageList ImageList
    * System.Drawing.ContentAlignment ImageAlign
    * System.Windows.Forms.ImeMode ImeMode
    * Int32 PreferredHeight
    * Int32 PreferredWidth
    * Boolean TabStop
    * System.Drawing.ContentAlignment TextAlign
    * System.String Text
    * Boolean UseCompatibleTextRendering
    * Boolean UseMnemonic
    * System.Windows.Forms.AccessibleObject AccessibilityObject
    * System.String AccessibleDefaultActionDescription
    * System.String AccessibleDescription
    * System.String AccessibleName
    * System.Windows.Forms.AccessibleRole AccessibleRole
    * Boolean AllowDrop
    * System.Windows.Forms.AnchorStyles Anchor
    * System.Drawing.Point AutoScrollOffset
    * System.Windows.Forms.Layout.LayoutEngine LayoutEngine
    * System.Drawing.Color BackColor
    * System.Windows.Forms.BindingContext BindingContext
    * Int32 Bottom
    * System.Drawing.Rectangle Bounds
    * Boolean CanFocus
    * Boolean CanSelect
    * Boolean Capture
    * Boolean CausesValidation
    * System.Drawing.Rectangle ClientRectangle
    * System.Drawing.Size ClientSize
    * System.String CompanyName
    * Boolean ContainsFocus
    * System.Windows.Forms.ContextMenu ContextMenu
    * System.Windows.Forms.ContextMenuStrip ContextMenuStrip
    * ControlCollection Controls
    * Boolean Created
    * System.Windows.Forms.Cursor Cursor
    * System.Windows.Forms.ControlBindingsCollection DataBindings
    * Int32 DeviceDpi
    * System.Drawing.Rectangle DisplayRectangle
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
    * System.Drawing.Point Location
    * System.Windows.Forms.Padding Margin
    * System.Drawing.Size MaximumSize
    * System.Drawing.Size MinimumSize
    * System.String Name
    * System.Windows.Forms.Control Parent
    * System.String ProductName
    * System.String ProductVersion
    * Boolean RecreatingHandle
    * System.Drawing.Region Region
    * Int32 Right
    * System.Windows.Forms.RightToLeft RightToLeft
    * System.ComponentModel.ISite Site
    * System.Drawing.Size Size
    * Int32 TabIndex
    * System.Object Tag
    * Int32 Top
    * System.Windows.Forms.Control TopLevelControl
    * Boolean UseWaitCursor
    * Boolean Visible
    * Int32 Width
    * System.Windows.Forms.IWindowTarget WindowTarget
    * System.Drawing.Size PreferredSize
    * System.Windows.Forms.Padding Padding
    * System.ComponentModel.IContainer Container
    * System.EventHandler AutoSizeChanged
    * System.EventHandler BackgroundImageChanged
    * System.EventHandler BackgroundImageLayoutChanged
    * System.EventHandler ImeModeChanged
    * System.Windows.Forms.KeyEventHandler KeyUp
    * System.Windows.Forms.KeyEventHandler KeyDown
    * System.Windows.Forms.KeyPressEventHandler KeyPress
    * System.EventHandler TabStopChanged
    * System.EventHandler TextAlignChanged
    * System.EventHandler BackColorChanged
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
    * System.EventHandler MarginChanged
    * System.EventHandler RegionChanged
    * System.EventHandler RightToLeftChanged
    * System.EventHandler SizeChanged
    * System.EventHandler TabIndexChanged
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
    * System.EventHandler Disposed
# .
  ## Members
    * System.String ()
    * Void (System.String)
    * Void ()
    * Void ()
    * Void ()
    * Void (System.String)
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
    * Boolean get_AutoSize()
    * Void set_AutoSize(Boolean)
    * Void add_AutoSizeChanged(System.EventHandler)
    * Void remove_AutoSizeChanged(System.EventHandler)
    * System.Drawing.Point get_AutoScrollOffset()
    * Void set_AutoScrollOffset(System.Drawing.Point)
    * System.Windows.Forms.Layout.LayoutEngine get_LayoutEngine()
    * System.Drawing.Color get_BackColor()
    * Void set_BackColor(System.Drawing.Color)
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
    * System.Windows.Forms.BindingContext get_BindingContext()
    * Void set_BindingContext(System.Windows.Forms.BindingContext)
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
    * System.Drawing.Rectangle get_DisplayRectangle()
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
    * System.Drawing.Size get_MaximumSize()
    * Void set_MaximumSize(System.Drawing.Size)
    * System.Drawing.Size get_MinimumSize()
    * Void set_MinimumSize(System.Drawing.Size)
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
    * System.String get_Text()
    * Void set_Text(System.String)
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
    * System.String ToString()
    * System.Object GetLifetimeService()
    * System.Object InitializeLifetimeService()
    * System.Runtime.Remoting.ObjRef CreateObjRef(System.Type)
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(System.String)
    * System.String Text
    * System.Windows.Forms.AccessibleObject AccessibilityObject
    * System.String AccessibleDefaultActionDescription
    * System.String AccessibleDescription
    * System.String AccessibleName
    * System.Windows.Forms.AccessibleRole AccessibleRole
    * Boolean AllowDrop
    * System.Windows.Forms.AnchorStyles Anchor
    * Boolean AutoSize
    * System.Drawing.Point AutoScrollOffset
    * System.Windows.Forms.Layout.LayoutEngine LayoutEngine
    * System.Drawing.Color BackColor
    * System.Drawing.Image BackgroundImage
    * System.Windows.Forms.ImageLayout BackgroundImageLayout
    * System.Windows.Forms.BindingContext BindingContext
    * Int32 Bottom
    * System.Drawing.Rectangle Bounds
    * Boolean CanFocus
    * Boolean CanSelect
    * Boolean Capture
    * Boolean CausesValidation
    * System.Drawing.Rectangle ClientRectangle
    * System.Drawing.Size ClientSize
    * System.String CompanyName
    * Boolean ContainsFocus
    * System.Windows.Forms.ContextMenu ContextMenu
    * System.Windows.Forms.ContextMenuStrip ContextMenuStrip
    * ControlCollection Controls
    * Boolean Created
    * System.Windows.Forms.Cursor Cursor
    * System.Windows.Forms.ControlBindingsCollection DataBindings
    * Int32 DeviceDpi
    * System.Drawing.Rectangle DisplayRectangle
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
    * System.Drawing.Point Location
    * System.Windows.Forms.Padding Margin
    * System.Drawing.Size MaximumSize
    * System.Drawing.Size MinimumSize
    * System.String Name
    * System.Windows.Forms.Control Parent
    * System.String ProductName
    * System.String ProductVersion
    * Boolean RecreatingHandle
    * System.Drawing.Region Region
    * Int32 Right
    * System.Windows.Forms.RightToLeft RightToLeft
    * System.ComponentModel.ISite Site
    * System.Drawing.Size Size
    * Int32 TabIndex
    * Boolean TabStop
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
    * System.EventHandler MarginChanged
    * System.EventHandler RegionChanged
    * System.EventHandler RightToLeftChanged
    * System.EventHandler SizeChanged
    * System.EventHandler TabIndexChanged
    * System.EventHandler TabStopChanged
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
# .
  ## Members
    * . ()
    * Void (.)
    * System.String ()
    * Void (System.String)
    * System.Drawing.Image ()
    * Void (System.Drawing.Image)
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
    * Boolean get_AutoSize()
    * Void set_AutoSize(Boolean)
    * Void add_AutoSizeChanged(System.EventHandler)
    * Void remove_AutoSizeChanged(System.EventHandler)
    * System.Drawing.Point get_AutoScrollOffset()
    * Void set_AutoScrollOffset(System.Drawing.Point)
    * System.Windows.Forms.Layout.LayoutEngine get_LayoutEngine()
    * System.Drawing.Color get_BackColor()
    * Void set_BackColor(System.Drawing.Color)
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
    * System.Windows.Forms.BindingContext get_BindingContext()
    * Void set_BindingContext(System.Windows.Forms.BindingContext)
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
    * System.Drawing.Rectangle get_DisplayRectangle()
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
    * System.Drawing.Size get_MaximumSize()
    * Void set_MaximumSize(System.Drawing.Size)
    * System.Drawing.Size get_MinimumSize()
    * Void set_MinimumSize(System.Drawing.Size)
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
    * System.String get_Text()
    * Void set_Text(System.String)
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
    * System.String ToString()
    * System.Object GetLifetimeService()
    * System.Object InitializeLifetimeService()
    * System.Runtime.Remoting.ObjRef CreateObjRef(System.Type)
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Void .ctor(System.String)
    * . IconState
    * System.String Text
    * System.Drawing.Image Image
    * System.Windows.Forms.AccessibleObject AccessibilityObject
    * System.String AccessibleDefaultActionDescription
    * System.String AccessibleDescription
    * System.String AccessibleName
    * System.Windows.Forms.AccessibleRole AccessibleRole
    * Boolean AllowDrop
    * System.Windows.Forms.AnchorStyles Anchor
    * Boolean AutoSize
    * System.Drawing.Point AutoScrollOffset
    * System.Windows.Forms.Layout.LayoutEngine LayoutEngine
    * System.Drawing.Color BackColor
    * System.Drawing.Image BackgroundImage
    * System.Windows.Forms.ImageLayout BackgroundImageLayout
    * System.Windows.Forms.BindingContext BindingContext
    * Int32 Bottom
    * System.Drawing.Rectangle Bounds
    * Boolean CanFocus
    * Boolean CanSelect
    * Boolean Capture
    * Boolean CausesValidation
    * System.Drawing.Rectangle ClientRectangle
    * System.Drawing.Size ClientSize
    * System.String CompanyName
    * Boolean ContainsFocus
    * System.Windows.Forms.ContextMenu ContextMenu
    * System.Windows.Forms.ContextMenuStrip ContextMenuStrip
    * ControlCollection Controls
    * Boolean Created
    * System.Windows.Forms.Cursor Cursor
    * System.Windows.Forms.ControlBindingsCollection DataBindings
    * Int32 DeviceDpi
    * System.Drawing.Rectangle DisplayRectangle
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
    * System.Drawing.Point Location
    * System.Windows.Forms.Padding Margin
    * System.Drawing.Size MaximumSize
    * System.Drawing.Size MinimumSize
    * System.String Name
    * System.Windows.Forms.Control Parent
    * System.String ProductName
    * System.String ProductVersion
    * Boolean RecreatingHandle
    * System.Drawing.Region Region
    * Int32 Right
    * System.Windows.Forms.RightToLeft RightToLeft
    * System.ComponentModel.ISite Site
    * System.Drawing.Size Size
    * Int32 TabIndex
    * Boolean TabStop
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
    * System.EventHandler MarginChanged
    * System.EventHandler RegionChanged
    * System.EventHandler RightToLeftChanged
    * System.EventHandler SizeChanged
    * System.EventHandler TabIndexChanged
    * System.EventHandler TabStopChanged
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
# .
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
    * . 
    * . 
    * . 
# .
  ## Members
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
    * Boolean get_AutoSize()
    * Void set_AutoSize(Boolean)
    * Void add_AutoSizeChanged(System.EventHandler)
    * Void remove_AutoSizeChanged(System.EventHandler)
    * System.Drawing.Point get_AutoScrollOffset()
    * Void set_AutoScrollOffset(System.Drawing.Point)
    * System.Windows.Forms.Layout.LayoutEngine get_LayoutEngine()
    * System.Drawing.Color get_BackColor()
    * Void set_BackColor(System.Drawing.Color)
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
    * System.Windows.Forms.BindingContext get_BindingContext()
    * Void set_BindingContext(System.Windows.Forms.BindingContext)
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
    * System.Drawing.Rectangle get_DisplayRectangle()
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
    * System.Drawing.Size get_MaximumSize()
    * Void set_MaximumSize(System.Drawing.Size)
    * System.Drawing.Size get_MinimumSize()
    * Void set_MinimumSize(System.Drawing.Size)
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
    * System.String get_Text()
    * Void set_Text(System.String)
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
    * System.String ToString()
    * System.Object GetLifetimeService()
    * System.Object InitializeLifetimeService()
    * System.Runtime.Remoting.ObjRef CreateObjRef(System.Type)
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Windows.Forms.AccessibleObject AccessibilityObject
    * System.String AccessibleDefaultActionDescription
    * System.String AccessibleDescription
    * System.String AccessibleName
    * System.Windows.Forms.AccessibleRole AccessibleRole
    * Boolean AllowDrop
    * System.Windows.Forms.AnchorStyles Anchor
    * Boolean AutoSize
    * System.Drawing.Point AutoScrollOffset
    * System.Windows.Forms.Layout.LayoutEngine LayoutEngine
    * System.Drawing.Color BackColor
    * System.Drawing.Image BackgroundImage
    * System.Windows.Forms.ImageLayout BackgroundImageLayout
    * System.Windows.Forms.BindingContext BindingContext
    * Int32 Bottom
    * System.Drawing.Rectangle Bounds
    * Boolean CanFocus
    * Boolean CanSelect
    * Boolean Capture
    * Boolean CausesValidation
    * System.Drawing.Rectangle ClientRectangle
    * System.Drawing.Size ClientSize
    * System.String CompanyName
    * Boolean ContainsFocus
    * System.Windows.Forms.ContextMenu ContextMenu
    * System.Windows.Forms.ContextMenuStrip ContextMenuStrip
    * ControlCollection Controls
    * Boolean Created
    * System.Windows.Forms.Cursor Cursor
    * System.Windows.Forms.ControlBindingsCollection DataBindings
    * Int32 DeviceDpi
    * System.Drawing.Rectangle DisplayRectangle
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
    * System.Drawing.Point Location
    * System.Windows.Forms.Padding Margin
    * System.Drawing.Size MaximumSize
    * System.Drawing.Size MinimumSize
    * System.String Name
    * System.Windows.Forms.Control Parent
    * System.String ProductName
    * System.String ProductVersion
    * Boolean RecreatingHandle
    * System.Drawing.Region Region
    * Int32 Right
    * System.Windows.Forms.RightToLeft RightToLeft
    * System.ComponentModel.ISite Site
    * System.Drawing.Size Size
    * Int32 TabIndex
    * Boolean TabStop
    * System.Object Tag
    * System.String Text
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
    * System.EventHandler MarginChanged
    * System.EventHandler RegionChanged
    * System.EventHandler RightToLeftChanged
    * System.EventHandler SizeChanged
    * System.EventHandler TabIndexChanged
    * System.EventHandler TabStopChanged
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
# .
  ## Members
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
    * Boolean get_AutoSize()
    * Void set_AutoSize(Boolean)
    * Void add_AutoSizeChanged(System.EventHandler)
    * Void remove_AutoSizeChanged(System.EventHandler)
    * System.Drawing.Point get_AutoScrollOffset()
    * Void set_AutoScrollOffset(System.Drawing.Point)
    * System.Windows.Forms.Layout.LayoutEngine get_LayoutEngine()
    * System.Drawing.Color get_BackColor()
    * Void set_BackColor(System.Drawing.Color)
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
    * System.Windows.Forms.BindingContext get_BindingContext()
    * Void set_BindingContext(System.Windows.Forms.BindingContext)
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
    * System.Drawing.Rectangle get_DisplayRectangle()
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
    * System.Drawing.Size get_MaximumSize()
    * Void set_MaximumSize(System.Drawing.Size)
    * System.Drawing.Size get_MinimumSize()
    * Void set_MinimumSize(System.Drawing.Size)
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
    * System.String get_Text()
    * Void set_Text(System.String)
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
    * System.String ToString()
    * System.Object GetLifetimeService()
    * System.Object InitializeLifetimeService()
    * System.Runtime.Remoting.ObjRef CreateObjRef(System.Type)
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.Windows.Forms.AccessibleObject AccessibilityObject
    * System.String AccessibleDefaultActionDescription
    * System.String AccessibleDescription
    * System.String AccessibleName
    * System.Windows.Forms.AccessibleRole AccessibleRole
    * Boolean AllowDrop
    * System.Windows.Forms.AnchorStyles Anchor
    * Boolean AutoSize
    * System.Drawing.Point AutoScrollOffset
    * System.Windows.Forms.Layout.LayoutEngine LayoutEngine
    * System.Drawing.Color BackColor
    * System.Drawing.Image BackgroundImage
    * System.Windows.Forms.ImageLayout BackgroundImageLayout
    * System.Windows.Forms.BindingContext BindingContext
    * Int32 Bottom
    * System.Drawing.Rectangle Bounds
    * Boolean CanFocus
    * Boolean CanSelect
    * Boolean Capture
    * Boolean CausesValidation
    * System.Drawing.Rectangle ClientRectangle
    * System.Drawing.Size ClientSize
    * System.String CompanyName
    * Boolean ContainsFocus
    * System.Windows.Forms.ContextMenu ContextMenu
    * System.Windows.Forms.ContextMenuStrip ContextMenuStrip
    * ControlCollection Controls
    * Boolean Created
    * System.Windows.Forms.Cursor Cursor
    * System.Windows.Forms.ControlBindingsCollection DataBindings
    * Int32 DeviceDpi
    * System.Drawing.Rectangle DisplayRectangle
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
    * System.Drawing.Point Location
    * System.Windows.Forms.Padding Margin
    * System.Drawing.Size MaximumSize
    * System.Drawing.Size MinimumSize
    * System.String Name
    * System.Windows.Forms.Control Parent
    * System.String ProductName
    * System.String ProductVersion
    * Boolean RecreatingHandle
    * System.Drawing.Region Region
    * Int32 Right
    * System.Windows.Forms.RightToLeft RightToLeft
    * System.ComponentModel.ISite Site
    * System.Drawing.Size Size
    * Int32 TabIndex
    * Boolean TabStop
    * System.Object Tag
    * System.String Text
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
    * System.EventHandler MarginChanged
    * System.EventHandler RegionChanged
    * System.EventHandler RightToLeftChanged
    * System.EventHandler SizeChanged
    * System.EventHandler TabIndexChanged
    * System.EventHandler TabStopChanged
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
# .
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
# .+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
# .+
  ## Members
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.String ToString()
    * System.Type GetType()
# .
  ## Members
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
    * Void .ctor(., .)
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
# .
  ## Members
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * Int32 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
    * System.String 
# .
  ## Members
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
    * Void .ctor(.)
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
# .
  ## Members
    * Boolean ()
    * Void (System.EventHandler)
    * Void (System.EventHandler)
    * Void (.)
    * Void (.)
    * Void (System.Net.IWebProxy)
    * System.String ToString()
    * Boolean Equals(System.Object)
    * Int32 GetHashCode()
    * System.Type GetType()
    * Void .ctor()
    * System.EventHandler DebuggerLaunched
    * . SendingReportFeedback
# SmartAssembly.Attributes.PoweredByAttribute
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
