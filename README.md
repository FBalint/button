
<div align="right">
  <details>
    <summary >🌐 Language</summary>
    <div>
      <div align="right">
        <p><a href="https://openaitx.github.io/view.html?user=FBalint&project=button&lang=en">English</a></p>
        <p><a href="https://openaitx.github.io/view.html?user=FBalint&project=button&lang=zh-CN">简体中文</a></p>
        <p><a href="https://openaitx.github.io/view.html?user=FBalint&project=button&lang=zh-TW">繁體中文</a></p>
        <p><a href="https://openaitx.github.io/view.html?user=FBalint&project=button&lang=ja">日本語</a></p>
        <p><a href="https://openaitx.github.io/view.html?user=FBalint&project=button&lang=ko">한국어</a></p>
        <p><a href="https://openaitx.github.io/view.html?user=FBalint&project=button&lang=hi">हिन्दी</a></p>
        <p><a href="https://openaitx.github.io/view.html?user=FBalint&project=button&lang=th">ไทย</a></p>
        <p><a href="https://openaitx.github.io/view.html?user=FBalint&project=button&lang=fr">Français</a></p>
        <p><a href="https://openaitx.github.io/view.html?user=FBalint&project=button&lang=de">Deutsch</a></p>
        <p><a href="https://openaitx.github.io/view.html?user=FBalint&project=button&lang=es">Español</a></p>
        <p><a href="https://openaitx.github.io/view.html?user=FBalint&project=button&lang=it">Itapano</a></p>
        <p><a href="https://openaitx.github.io/view.html?user=FBalint&project=button&lang=ru">Русский</a></p>
        <p><a href="https://openaitx.github.io/view.html?user=FBalint&project=button&lang=pt">Português</a></p>
        <p><a href="https://openaitx.github.io/view.html?user=FBalint&project=button&lang=nl">Nederlands</a></p>
        <p><a href="https://openaitx.github.io/view.html?user=FBalint&project=button&lang=pl">Polski</a></p>
        <p><a href="https://openaitx.github.io/view.html?user=FBalint&project=button&lang=ar">العربية</a></p>
        <p><a href="https://openaitx.github.io/view.html?user=FBalint&project=button&lang=fa">فارسی</a></p>
        <p><a href="https://openaitx.github.io/view.html?user=FBalint&project=button&lang=tr">Türkçe</a></p>
        <p><a href="https://openaitx.github.io/view.html?user=FBalint&project=button&lang=vi">Tiếng Việt</a></p>
        <p><a href="https://openaitx.github.io/view.html?user=FBalint&project=button&lang=id">Bahasa Indonesia</a></p>
      </div>
    </div>
  </details>
</div>

# 3D Pressable Button


A realistic 3D button component built with HTML, CSS, and SVG that simulates the feel of pressing a physical button. The button features smooth animations, customizable colors, and responsive interactions.


Created by [@BalintFerenczy](https://x.com/BalintFerenczy)

Inspired by the amazing work at [Resend](https://resend.com/)


## Features

- **Realistic 3D appearance** using layered SVG graphics
- **Smooth animations** with custom easing functions
- **Interactive states** - hover and press effects
- **Customizable colors** through CSS variables
- **Responsive design** that scales with container size

## Demo

The button responds to user interactions with three distinct states:
- **Normal**: The button in its resting position
- **Hover**: Subtle downward movement when mouse hovers over
- **Active**: Significant downward movement when pressed/clicked

## Usage

### Customization

The button can be easily customized using CSS custom properties:

```css
.frame {
    /* Button dimensions */
    width: 400px; 
    height: 400px; 

    /* Movement distances */
    --hover-travel: 3px;
    --press-travel: 40px;
    
    /* Color customization */
    --color: black;
    --brightness: 1;
    --blend-mode: color;

    /* Transition settings */
    --transition-duration: 0.4s;
    --transition-easing: ease-in-out;
}
```

#### Changing Button Text

Simply modify the text content:

```html
<p class="text">Click Me!</p>
```

#### Changing Button Size

Adjust the frame dimensions:

```css
.frame {
    width: 200px;
    height: 200px;
}
```

## License

This project is open source and available under the MIT License.

## Contributing

Feel free to fork this project and submit pull requests for improvements or new features!

## Author

Created by [@BalintFerenczy](https://x.com/BalintFerenczy)