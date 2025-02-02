# Constantes

CultureName es el tipo de código de país de idioma admitido para aplicar el formato de número.

```go
type CultureName byte
```

Esta sección define la enumeración de tipos de código de país admitida actualmente para aplicar el formato de número.

```go
const (
    CultureNameUnknown CultureName = iota
    CultureNameEnUS
    CultureNameZhCN
)
```

ChartType es el tipo de tipos de gráficos admitidos.

```go
type ChartType byte
```

Esta sección define la enumeración de tipos de gráficos admitidos actualmente:

```go
const (
    Area ChartType = iota
    AreaStacked
    AreaPercentStacked
    Area3D
    Area3DStacked
    Area3DPercentStacked
    Bar
    BarStacked
    BarPercentStacked
    Bar3DClustered
    Bar3DStacked
    Bar3DPercentStacked
    Bar3DConeClustered
    Bar3DConeStacked
    Bar3DConePercentStacked
    Bar3DPyramidClustered
    Bar3DPyramidStacked
    Bar3DPyramidPercentStacked
    Bar3DCylinderClustered
    Bar3DCylinderStacked
    Bar3DCylinderPercentStacked
    Col
    ColStacked
    ColPercentStacked
    Col3D
    Col3DClustered
    Col3DStacked
    Col3DPercentStacked
    Col3DCone
    Col3DConeClustered
    Col3DConeStacked
    Col3DConePercentStacked
    Col3DPyramid
    Col3DPyramidClustered
    Col3DPyramidStacked
    Col3DPyramidPercentStacked
    Col3DCylinder
    Col3DCylinderClustered
    Col3DCylinderStacked
    Col3DCylinderPercentStacked
    Doughnut
    Line
    Line3D
    Pie
    Pie3D
    PieOfPie
    BarOfPie
    Radar
    Scatter
    Surface3D
    WireframeSurface3D
    Contour
    WireframeContour
    Bubble
    Bubble3D
)
```

Relación de origen y espacio de nombres:

```go
const (
    ContentTypeAddinMacro                         = "application/vnd.ms-excel.addin.macroEnabled.main+xml"
    ContentTypeDrawing                            = "application/vnd.openxmlformats-officedocument.drawing+xml"
    ContentTypeDrawingML                          = "application/vnd.openxmlformats-officedocument.drawingml.chart+xml"
    ContentTypeMacro                              = "application/vnd.ms-excel.sheet.macroEnabled.main+xml"
    ContentTypeSheetML                            = "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet.main+xml"
    ContentTypeSpreadSheetMLChartsheet            = "application/vnd.openxmlformats-officedocument.spreadsheetml.chartsheet+xml"
    ContentTypeSpreadSheetMLComments              = "application/vnd.openxmlformats-officedocument.spreadsheetml.comments+xml"
    ContentTypeSpreadSheetMLPivotCacheDefinition  = "application/vnd.openxmlformats-officedocument.spreadsheetml.pivotCacheDefinition+xml"
    ContentTypeSpreadSheetMLPivotTable            = "application/vnd.openxmlformats-officedocument.spreadsheetml.pivotTable+xml"
    ContentTypeSpreadSheetMLSharedStrings         = "application/vnd.openxmlformats-officedocument.spreadsheetml.sharedStrings+xml"
    ContentTypeSpreadSheetMLTable                 = "application/vnd.openxmlformats-officedocument.spreadsheetml.table+xml"
    ContentTypeSpreadSheetMLWorksheet             = "application/vnd.openxmlformats-officedocument.spreadsheetml.worksheet+xml"
    ContentTypeTemplate                           = "application/vnd.openxmlformats-officedocument.spreadsheetml.template.main+xml"
    ContentTypeTemplateMacro                      = "application/vnd.ms-excel.template.macroEnabled.main+xml"
    ContentTypeVBA                                = "application/vnd.ms-office.vbaProject"
    ContentTypeVML                                = "application/vnd.openxmlformats-officedocument.vmlDrawing"
    NameSpaceDrawingMLMain                        = "http://schemas.openxmlformats.org/drawingml/2006/main"
    NameSpaceDublinCore                           = "http://purl.org/dc/elements/1.1/"
    NameSpaceDublinCoreMetadataInitiative         = "http://purl.org/dc/dcmitype/"
    NameSpaceDublinCoreTerms                      = "http://purl.org/dc/terms/"
    NameSpaceExtendedProperties                   = "http://schemas.openxmlformats.org/officeDocument/2006/extended-properties"
    NameSpaceXML                                  = "http://www.w3.org/XML/1998/namespace"
    NameSpaceXMLSchemaInstance                    = "http://www.w3.org/2001/XMLSchema-instance"
    SourceRelationshipChart                       = "http://schemas.openxmlformats.org/officeDocument/2006/relationships/chart"
    SourceRelationshipChartsheet                  = "http://schemas.openxmlformats.org/officeDocument/2006/relationships/chartsheet"
    SourceRelationshipComments                    = "http://schemas.openxmlformats.org/officeDocument/2006/relationships/comments"
    SourceRelationshipDialogsheet                 = "http://schemas.openxmlformats.org/officeDocument/2006/relationships/dialogsheet"
    SourceRelationshipDrawingML                   = "http://schemas.openxmlformats.org/officeDocument/2006/relationships/drawing"
    SourceRelationshipDrawingVML                  = "http://schemas.openxmlformats.org/officeDocument/2006/relationships/vmlDrawing"
    SourceRelationshipExtendProperties            = "http://schemas.openxmlformats.org/officeDocument/2006/relationships/extended-properties"
    SourceRelationshipHyperLink                   = "http://schemas.openxmlformats.org/officeDocument/2006/relationships/hyperlink"
    SourceRelationshipImage                       = "http://schemas.openxmlformats.org/officeDocument/2006/relationships/image"
    SourceRelationshipOfficeDocument              = "http://schemas.openxmlformats.org/officeDocument/2006/relationships/officeDocument"
    SourceRelationshipPivotCache                  = "http://schemas.openxmlformats.org/officeDocument/2006/relationships/pivotCacheDefinition"
    SourceRelationshipPivotTable                  = "http://schemas.openxmlformats.org/officeDocument/2006/relationships/pivotTable"
    SourceRelationshipSharedStrings               = "http://schemas.openxmlformats.org/officeDocument/2006/relationships/sharedStrings"
    SourceRelationshipTable                       = "http://schemas.openxmlformats.org/officeDocument/2006/relationships/table"
    SourceRelationshipVBAProject                  = "http://schemas.microsoft.com/office/2006/relationships/vbaProject"
    SourceRelationshipWorkSheet                   = "http://schemas.openxmlformats.org/officeDocument/2006/relationships/worksheet"
    StrictNameSpaceDocumentPropertiesVariantTypes = "http://purl.oclc.org/ooxml/officeDocument/docPropsVTypes"
    StrictNameSpaceDrawingMLMain                  = "http://purl.oclc.org/ooxml/drawingml/main"
    StrictNameSpaceExtendedProperties             = "http://purl.oclc.org/ooxml/officeDocument/extendedProperties"
    StrictNameSpaceSpreadSheet                    = "http://purl.oclc.org/ooxml/spreadsheetml/main"
    StrictSourceRelationship                      = "http://purl.oclc.org/ooxml/officeDocument/relationships"
    StrictSourceRelationshipChart                 = "http://purl.oclc.org/ooxml/officeDocument/relationships/chart"
    StrictSourceRelationshipComments              = "http://purl.oclc.org/ooxml/officeDocument/relationships/comments"
    StrictSourceRelationshipExtendProperties      = "http://purl.oclc.org/ooxml/officeDocument/relationships/extendedProperties"
    StrictSourceRelationshipImage                 = "http://purl.oclc.org/ooxml/officeDocument/relationships/image"
    StrictSourceRelationshipOfficeDocument        = "http://purl.oclc.org/ooxml/officeDocument/relationships/officeDocument"
    // ExtURIConditionalFormattings is the extLst child element
    // ([ISO/IEC29500-1:2016] section 18.2.10) of the worksheet element
    // ([ISO/IEC29500-1:2016] section 18.3.1.99) is extended by the addition of
    // new child ext elements ([ISO/IEC29500-1:2016] section 18.2.7)
    ExtURIConditionalFormattingRuleID = "{B025F937-C7B1-47D3-B67F-A62EFF666E3E}"
    ExtURIConditionalFormattings      = "{78C0D931-6437-407d-A8EE-F0AAD7539E65}"
    ExtURIDataValidations             = "{CCE6A557-97BC-4B89-ADB6-D9C93CAAB3DF}"
    ExtURIDrawingBlip                 = "{28A0092B-C50C-407E-A947-70E740481C1C}"
    ExtURIIgnoredErrors               = "{01252117-D84E-4E92-8308-4BE1C098FCBB}"
    ExtURIMacExcelMX                  = "{64002731-A6B0-56B0-2670-7721B7C09600}"
    ExtURIProtectedRanges             = "{FC87AEE6-9EDD-4A0A-B7FB-166176984837}"
    ExtURISlicerCachesListX14         = "{BBE1A952-AA13-448e-AADC-164F8A28A991}"
    ExtURISlicerListX14               = "{A8765BA9-456A-4DAB-B4F3-ACF838C121DE}"
    ExtURISlicerListX15               = "{3A4CF648-6AED-40f4-86FF-DC5316D8AED3}"
    ExtURISparklineGroups             = "{05C60535-1F16-4fd2-B633-F4F36F0B64E0}"
    ExtURISVG                         = "{96DAC541-7B7A-43D3-8B79-37D633B846F1}"
    ExtURITimelineRefs                = "{7E03D99C-DC04-49d9-9315-930204A7B6E9}"
    ExtURIWebExtensions               = "{F7C9EE02-42E1-4005-9D12-6889AFFD525C}"
)
```

Especificaciones y límites de Excel:

```go
const (
    MaxCellStyles        = 65430
    MaxColumns           = 16384
    MaxColumnWidth       = 255
    MaxFieldLength       = 255
    MaxFilePathLength    = 207
    MaxFormControlValue  = 30000
    MaxFontFamilyLength  = 31
    MaxFontSize          = 409
    MaxRowHeight         = 409
    MaxSheetNameLength   = 31
    MinColumns           = 1
    MinFontSize          = 1
    StreamChunkSize      = 1 << 24
    TotalCellChars       = 32767
    TotalRows            = 1048576
    TotalSheetHyperlinks = 65529
    UnzipSizeLimit       = 1000 << 24
)
```

Defina el tamaño de celda predeterminado y la unidad de medida EMU (unidades métricas inglesas):

```go
const (
    EMU int = 9525
)
```

Esta sección define los tipos de validación de datos.

```go
const (
    DataValidationTypeCustom
    DataValidationTypeDate
    DataValidationTypeDecimal
    DataValidationTypeTextLength
    DataValidationTypeTime
    DataValidationTypeWhole
)
```

Esta sección define los operadores de validación de datos.

```go
const (
    DataValidationOperatorBetween
    DataValidationOperatorEqual
    DataValidationOperatorGreaterThan
    DataValidationOperatorGreaterThanOrEqual
    DataValidationOperatorLessThan
    DataValidationOperatorLessThanOrEqual
    DataValidationOperatorNotBetween
    DataValidationOperatorNotEqual
)
```

CellType es el tipo de valor de celda.

```go
const (
    CellTypeUnset CellType = iota
    CellTypeBool
    CellTypeDate
    CellTypeError
    CellTypeFormula
    CellTypeInlineString
    CellTypeNumber
    CellTypeSharedString
)
```

ColorMappingType es el tipo de transformación de color.

```go
const (
    ColorMappingTypeLight1 ColorMappingType = iota
    ColorMappingTypeDark1
    ColorMappingTypeLight2
    ColorMappingTypeDark2
    ColorMappingTypeAccent1
    ColorMappingTypeAccent2
    ColorMappingTypeAccent3
    ColorMappingTypeAccent4
    ColorMappingTypeAccent5
    ColorMappingTypeAccent6
    ColorMappingTypeHyperlink
    ColorMappingTypeFollowedHyperlink
    ColorMappingTypeUnsetValue int = -1
)
```
