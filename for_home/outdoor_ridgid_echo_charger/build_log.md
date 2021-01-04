# Amazon Echo Power from Ridgid Battery

Build power source for Amazon Echo using a standard Ridgid power tool battery. Unit needs to be able to be used outdoors on warm summer days.




## Parts

* DC/DC 18v to 5V USB - [Buck Converter](https://www.amazon.com/dp/B01HXU1C6U/ref=pe_1098610_137717230_cm_rv_eml_rv0_dp)
* 3D print using PETG




## Log

---

Dec 27 2020  

Made some spare battery holders for the shop

![printed holder](images/ridgid_spare_battery_holder.JPG)
![printed holder](images/ridgid_spare_battery_holder_b.JPG)
![printed holder](images/ridgid_spare_battery_holder_c.JPG)

---

Dec 29 2020  

Got buck convert from Amazon. Soldered on some wires and connectors and did some initial testing.

![Initial Test](images/Ridgid_Echo_Dot_Initial_test.gif)

--- 

Dec 30 2020  

Tried various buck converter fixture holders.

![](images/buck_converter_designs2.JPG)


---

Dec 31 2020  

Did thermal testing of buck converter under 4x of expected load.

**Test Setup**

![Test Setup](images/thermal_load_test_setup.JPG)

**2.5 Amps**

Unit gets very hot under this load (244°F)

![High Load Test](images/thermal_test_2.01a_load_hot.jpeg)

---

Jan 1 2021  

Worked on pressure fit battery connector. Tried lots of different methods to slide connect batter to thermals.

Initial was using steel endocarps from crescent rolls cans. But generally the metal was too then to hold the shape needed


Finally ended up with slots in part and folded up paper clip and a screw to hold it together

![Crescent Rolls Part](images/battery_connector_early.JPG)
![Functional Battery Clip](images/battery_connector_prototype.JPG)


Did more thermal testing under expected load + 15%. Unit stayed fairly cool at 108°F

![Normal Load Thermal Test](images/expected_load_termal_test_6.5hrs.JPG)

---

Jan 2 2021  

Working on merging Buck Converter and Battery Clip into single unit.

Start preparing print bed for PETG printing

![Buck/Clip Merge](images/buck_clip_merge.PNG)