---
-api-id: M:Microsoft.UI.Xaml.Input.RightTappedRoutedEventArgs.GetPosition(Microsoft.UI.Xaml.UIElement)
-api-type: winrt method
---

<!-- Method syntax
public Windows.Foundation.Point GetPosition(Microsoft.UI.Xaml.UIElement relativeTo)
-->

# Microsoft.UI.Xaml.Input.RightTappedRoutedEventArgs.GetPosition

## -description
Returns the x- and y-coordinates of the pointer position, optionally evaluated against a coordinate origin of a supplied [UIElement](../microsoft.ui.xaml/uielement.md).

## -parameters
### -param relativeTo
Any [UIElement](../microsoft.ui.xaml/uielement.md)-derived object that is connected to the same object tree. To specify the object relative to the overall coordinate system, use a *relativeTo* value of `null`.

## -returns
A `Point` that represents the current x- and y-coordinates of the mouse pointer position. If `null` was passed as *relativeTo*, this coordinate is for the overall window. If a *relativeTo* value other than `null` was passed, this coordinate is relative to the object referenced by *relativeTo*.

## -remarks

## -examples

## -see-also
[Point](/uwp/api/windows.foundation.point), [RightTapped](../microsoft.ui.xaml/uielement_righttapped.md), [OnRightTapped](/uwp/api/windows.ui.xaml.controls.control.onrighttapped(windows.ui.xaml.input.righttappedroutedeventargs)), [HoldingRoutedEventArgs](holdingroutedeventargs.md)
