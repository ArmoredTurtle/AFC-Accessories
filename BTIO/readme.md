


The BoxTurtle IO (BTIO) module simplifies the integration of your BoxTurtle multi-color system with your 3D printer by serving as a centralized hub for all essential connections. It offers a clean, dependable interface for linking the printer, connecting the toolhead buffer, and supporting daisy-chained configurations for multi-unit expansion. BTIO also enables external power delivery when operating over USB. This modular design supports scalable, intelligent filament handling while keeping wiring complexity to a minimum.
![BTIO_R](https://github.com/user-attachments/assets/f1d26f95-eb7c-4e87-b8d6-1b3ea9ceb362)
![BTIO](https://github.com/user-attachments/assets/559d5ccb-cb8c-48d5-b46f-b38d94671d4d)
# PAY ATTENTION TO THE WIRING OF THE TN PORT
Ensure that ground and signal lines are not mixed. 
With the exception of USB lines, all ground connections on this board share a common ground. While only one ground is electrically necessary for the toolhead buffer, the “TN” port includes two ground pins to mirror the original connector layout. This design allows users to repin their toolhead buffer cable into a new single connector—without the need for soldering—when adapting it for use with the BTIO board.

# Assembly 
Use in place of "right_rear_skirt". Install two heatset inserts into "[a]_opttion_plate".
Secure the option plate to the right rear skirt *BEFORE* installing the BTIO board with two M3x6 SHCS. Secure the BTIO to the assembly with two additional M3x6 SHCS (these ones are threaded into plastic, do not overtighten)!
