
module TB_encoder4_2;

	// Inputs
	reg E;
	reg [3:0] I;

	// Outputs
	wire [1:0] Y;

	// Instantiate the Unit Under Test (UUT)
	encoder4_2 uut (
		.E(E), 
		.I(I), 
		.Y(Y)
	);

	initial begin
		// Initialize Inputs
		E = 0;
		I = 0;

		// Wait 100 ns for global reset to finish
		#1000;
        
		  E = 1;				
		// Add stimulus here
			end				
      
		           always #100 I[0] = ~I[0];
                                 always #200 I[1] = ~I[1];
			always #400 I[2] = ~I[2];						
			always #800 I[3] = ~I[3];
							
endmodule
