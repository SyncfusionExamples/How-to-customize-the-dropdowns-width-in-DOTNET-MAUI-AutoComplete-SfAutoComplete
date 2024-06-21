# How-to-customize-the-dropdowns-width-in-DOTNET-MAUI-AutoComplete-SfAutoComplete
This repository contains a sample demonstrating of customizing the dropdown's width in .NET MAUI AutoComplete
## DropdownPlacement support in .NET MAUI AutoComplete (SfAutoComplete)
 We can change the dropdown's width in SfAutoComplete by changing the DropdownWidth value.

The following code example illustrate how to set DropdownWidth in SfAutoComplete.

**XAML**
```
<editors:SfAutocomplete DropdownWidth="250"
                        HeightRequest="40"
                       WidthRequest="200">
    <editors:SfAutocomplete.ItemsSource>
        <x:Array Type="{x:Type x:String}">
            <x:String>Uganda</x:String>
            <x:String>Ukraine</x:String>
            <x:String>United States</x:String>
            <x:String>United Kingdom</x:String>
            <x:String>Uzbekistan</x:String>
        </x:Array>
    </editors:SfAutocomplete.ItemsSource>
</editors:SfAutocomplete>

```
