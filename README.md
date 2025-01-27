# tida-050047-ledcontroller
This board is designed as a prototype for powering your projects using four 18650 lithium-ion battery cells. It delivers a 5V output with a maximum current of 5A. The cells are configured in a 4S1P (4-series, 1-parallel) arrangement, balanced and charged via USB-C Power Delivery (PD) with the maximum charging current supported by the cells.
This design is based on the [TIDA-050047](https://www.ti.com/tool/TIDA-050047#design-products) reference design by Texas Instruments.


#### Parts that I have in stock:
```
$ nu
$ open LCSC_AllParts.csv | select "Type" "Value" "Rating" "Package" "LCSC Part Number" "Description" | sort-by "Type"
```

