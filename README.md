<img src="https://dl.dropbox.com/u/1255340/lunchbox-logo-720.jpg" width="420" height="420" align="right">

# LUNCHBOX CSS

**Semantic CSS Framework for Rapid Prototyping and Responsive Layouts**

…more documentation coming! for now check out the example files


#Usage

### Basic Structure

A **.lunchbox** class must always wrap a **.lunch** class, and vice versa

	<div class="lunchbox">
		<div class="lunch">{content}</div>
	</div>


###Breakpoints


	<body>
	
		<div class="backpack">

			<header class="lunchbox"> {header content} </header>

			<div class="lunchbox">
			
				<div class="lunch one_third at_700_one_quarter">
					{content left}				
				</div>
			
				<div class="lunch two_thirds at_700_three_quarters">
					{content right}
				</div>
			
			</div>
		
			<footer class="lunchbox"> {footer content} </footer>
		
		</div>
		
	</body>	