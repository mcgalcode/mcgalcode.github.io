<header>
    <div class="header-wrapper">
        <div class="header-avatar">
            {% if site.avatar %}
                <a class="image avatar"><img src="{{ site.avatar }}" alt="avatar" /></a>
            {% endif %}
            <div class="avatar-subtitle">
                <h1><a href="/">{{ site.title }}</a></h1>
                {% if site.email %}
                <email class="avatar-email">{{ site.email }}</email>
                {% endif %}                
            </div>
        </div>
        
        <div class="header-contact">
            {% if site.position %}
            <position style="font-size:1.10rem;">{{ site.position }}</position>
            <br>
            {% endif %}
            {% if site.affiliation %}
            <div>
                <a href="{{ site.affiliation_link }}" style="margin-top: 0.5em; display: block;" rel="noopener"><autocolor>{{ site.affiliation }}</autocolor></a>
                <br>
                {% endif %}
                {% if site.email %}
                <email class="affiliation-email" style="margin-top: 0.1em; display: block;">{{ site.email }}</email>
                {% endif %}
            </div>
            <br>
            <br>
            <div class="social-icons header-social-icons">
                {% if site.google_scholar %}
                <a style="margin: 0 5px 0 0" href="{{ site.google_scholar }}">
                    <i class="ai ai-google-scholar" style="font-size:1.2rem"></i>
                </a>  
                {% endif %}   
                {% if site.cv_link %}
                <a style="margin: 0 5px 0 0" href="{{ site.cv_link }}">
                    <i class="ai ai-cv" style="font-size:1.3rem;"></i>
                </a>
                {% endif %}

                {% if site.github_link %}
                <a style="margin: 0 5px 0 0" href="{{ site.github_link }}">
                    <i class="fab fa-github"></i>
                </a>
                {% endif %}

                {% if site.linkedin %}
                <a style="margin: 0 5px 0 0" href="{{ site.linkedin }}">
                    <i class="fab fa-linkedin"></i>
                </a>
                {% endif %}

                {% if site.twitter %}
                <a style="margin: 0 0 0 0" href="{{ site.twitter }}">
                    <i class="fab fa-x-twitter"></i>
                </a>
                {% endif %}
            </div>         
        </div>
    <br>
    </div>
</header>