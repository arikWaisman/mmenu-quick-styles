# mmenu-quick-styles

pull the file into your project with sass. Add a class or Id to your Nav element and use the mixin inside (replace $some-color with an values you choose):

#my-nav-element{

	@include MMenuStyles($background: $some-color, $text-and-borders: $some-color, $hover-background: $some-color, $active-and-hover-text: $some-color)

}
