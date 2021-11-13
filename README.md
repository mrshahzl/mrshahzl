<h6 align="center">
  <img align="center" alt="irene" width="600px" src="https://i.pinimg.com/originals/ef/f3/73/eff373557e12d3f256af334580d1ecf6.gif">
</h5>
<h2 align="center">Hello, I'm Marsha/Hazel !</h2>
  <h3>Hello!</h3>

<h5 align="center">
  <code>
    <a href="https://open.spotify.com/user/kodr6alxrx58w5ez1huh6n04l" title="Spotify"><img width="22" src="https://i.pinimg.com/originals/d5/dc/8a/d5dc8a3543bc32becf4c36bd8049cfb8.jpg"> Spotify</a></code>
  <code><a href="https://www.pinterest.com/Mrshahzl_/" title="Pinterest"><img width="22" src="https://i.pinimg.com/originals/d3/1c/34/d31c34772f9d85e371275afa465f32e6.jpg"> Pinterest</a></code>
  <code><a href="https://www.instagram.com/mrshahzl_/" title="Instagram"><img width="22" src="https://i.pinimg.com/originals/bd/c5/d8/bdc5d81a5ddb44c0a6ddac8e0c32d266.jpg"> Instagram</a></code>
</h5>
A57A5A

![Marsha's GitHub stats!](https://github-readme-stats.vercel.app/api?username=mrshahzl&show_icons=true&count_private=true&title_color=E8DCB5&bg_color=A67A5B&text_color=000000&icon_color=FFFFFF&count_private=True&custom_title=Marshmallows)

### I am currently Learning and using:
<h5 align="center">
  <img src="https://img.shields.io/badge/python%20-%2314354C.svg?&style=for-the-badge&logo=python&logoColor=white">   <img src="https://img.shields.io/badge/javascript%20-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E">   <img src="https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white">   <img src="https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white">   <img src="http://img.shields.io/badge/-VS%20Code-000000?style=for-the-badge&logo=Visual-studio-code&logoColor=blue">
  </h5>
<svg width="495" height="160" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
    <foreignObject width="495" height="160">
        <div xmlns="http://www.w3.org/1999/xhtml" class="container">
            <style>
                /* CSS Reset */
                html, body, div, span, h1, p, a, img {
                    margin: 0;
                    padding: 0;
                    border: 0;
                    font-size: 100%;
                    font: inherit;
                    vertical-align: baseline;
                }
                /* Actual Styles */
                main {
                    display: flex;
                    padding: 20px;
                    border-radius: 5px;
                    {% if theme == 'dark' %}
                        background: #161B22;
                    {% else %}
                        background: #F6F8FA;
                    {% endif %}
                }
                .scan-code {
                    transform-origin: top right;
                    transform: rotate(270deg) translateY(-120px);
                    width: 120px;
                    height: 100%;
                    border-radius: 5px;
                    {% if theme == 'dark' %}
                        filter: invert(100%);
                    {% endif %}
                }
                aside {
                    width: 485px;
                    display: flex;
                    position: relative;
                    {% if scan_code %}
                        left: -70px;
                    {% endif %}
                }
                .cover {
                    width: 120px;
                    height: 120px;
                    {% if spin %}                    border-radius: 50%;
                    animation: spin 0ms -800ms linear infinite;
                    animation-duration: 10s;
                    {% else %}
                    border-radius: 10px;
                    {% endif %}
                    {% if theme == 'dark' %}
                        box-shadow: 0 0 10px 5px #1b2027;
                    {% else %}
                        box-shadow: 0 0 10px 5px #f1f3f5;
                    {% endif %}
                }
                section {
                    padding-left: 20px;
                    width: 100%;
                    display: flex;
                    flex-direction: column;
                    justify-content: space-between;
                    align-items: center;
                }
                .info {
                    margin-top: 16px;
                    display: flex;
                    flex-direction: column;
                    align-items: center;
                    font-family: -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica, Arial, sans-serif, Apple Color Emoji, Segoe UI Emoji;
                }
                .top {
                    display: flex;
                    align-items: center;
                }
                h1 {
                    font-size: 20px;
                    font-weight: 600;
                    white-space: nowrap;
                    text-overflow: ellipsis;
                    display: block;
                    overflow: hidden;
                    max-width: 260px;
                    {% if not scan_code %}
                        margin-left: 10px;
                    {% endif %}
                    {% if theme == 'dark' %}
                        color: aliceblue;
                    {% else %}
                        color: #161B22;;
                    {% endif %}
                }
                p {
                    margin-top: 5px;
                    font-size: 18px;
                    font-weight: 500;
                    white-space: nowrap;
                    text-overflow: ellipsis;
                    display: block;
                    overflow: hidden;
                    max-width: 260px;
                    {% if theme == 'dark' %}
                        color: rgba(240, 248, 255, calc(2/3));
                    {% else %}
                        color: rgba(22, 27, 34, calc(2/3));
                    {% endif %}
                }
                .logo {
                    width: 24px;
                    height: 24px;
                }
                .bar-container {
                    display: flex;
                    animation: rainbow 0ms -800ms linear infinite;
                }
                .bar {
                    border-radius: 3px 3px 0 0;
                    height: 30px;
                    transform-origin: bottom;
                    animation: resize 0ms -800ms ease-in-out infinite alternate;
                    {% if scan_code %}
                        width: 21px;
                    {% else %}
                        width: 20px;
                    {% endif %}
                }
                .bar:not(:first-child) {
                    margin-left: 6px;
                }
                @keyframes spin {
                    100% { transform: rotate(360deg) }
                }
                @keyframes rainbow {
                    100% { filter: hue-rotate(360deg) }
                }
                @keyframes resize {
                    0% {
                        transform: scaleY(0);
                        opacity: .05;
                    } 100% {
                        transform: scaleY(1);
                        opacity: .95;
                    }
                }
            </style>
            <main>
                {% if scan_code %}
                    <img class="scan-code" src="data:image/png;base64, {{scan_code}}" alt="Scan Code" />
                {% endif %}
                <aside>
                    <img class="cover" src="data:image/png;base64, {{image}}" alt="Cover Image" />
                    <section>
                        <div class="info">
                            <div class="top">
                                {% if not scan_code %}
                                    <img class="logo" src="data:image/png;base64, {{logo}}" alt="Spotify Logo" />
                                {% endif %}
                                <h1>{{song}}</h1>
                            </div>
                            <p>{{artist}}</p>
                        </div>
                        <div class="bar-container">
                            {{bars|safe}}
                        </div>
                    </section>
                </aside>
            </main>
        </div>
    </foreignObject>
</svg>
