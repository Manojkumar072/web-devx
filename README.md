<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BlogSpot - Home</title>
    <link rel="stylesheet" href="assets/CSS/style.css">
</head>
<body>
    <header>
        <div class="logo">BlogSpot</div>
        <nav>
            <ul>
                <li><a href="index.html" class="active">Home</a></li>
                <li><a href="my-blogs.html">My Blogs</a></li>
                <li><a href="login.html">Login</a></li>
                <li><a href="signup.html">Sign Up</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <!-- Hero Section -->
        <section class="hero">
            <h1>Thoughts, Stories & Ideas</h1>
            <p>Welcome to my blog where I share my thoughts, stories, and ideas on web development, design, and more. Stay tuned for insightful articles and tutorials.</p>
            <a href="my-blogs.html" class="cta-btn">View Blogs</a>
        </section>
        <div class="filter-section">
            <h3>Filter Blogs</h3>
            <div class="filter-options">
                <select class="filter-dropdown" id="category-filter">
                    <option value="">All Categories</option>
                    <option value="webdev">Web Development</option>
                    <option value="design">Design</option>
                    <option value="javascript">JavaScript</option>
                    <option value="css">CSS</option>
                </select>
                
                <select class="filter-dropdown" id="date-filter">
                    <option value="">Any Date</option>
                    <option value="today">Today</option>
                    <option value="week">This Week</option>
                    <option value="month">This Month</option>
                </select>
                
                <input type="text" class="filter-search" placeholder="Search blogs...">
                <button class="filter-btn">Apply</button>
            </div>
        </div>

        <div class="blog-container">
            <div class="blog-card">
                <div class="blog-header">
                    <img src="/assets/imgs/profile.jpeg" alt="User avatar" class="avatar">
                    <div class="blog-info">
                        <h3>The Future of Web Development</h3>
                        <p class="author">By Rohith • 2 days ago • Web Development</p>
                    </div>
                </div>
                <div class="blog-content">
                    <p>Web development continues to evolve at a rapid pace. With new frameworks and technologies emerging regularly, it's crucial to stay updated...</p>
                </div>
            </div>

            <div class="blog-card">
                <div class="blog-header">
                    <img src="/assets/imgs/profile.jpeg" alt="User avatar" class="avatar">
                    <div class="blog-info">
                        <h3>Mastering CSS Animations</h3>
                        <p class="author">By Harsha • 3 days ago • CSS</p>
                    </div>
                </div>
                <div class="blog-content">
                    <p>CSS animations can bring life to your website. In this article, I'll share some advanced techniques for creating smooth, engaging animations without compromising performance...</p>
                </div>
            </div>

            <div class="blog-card">
                <div class="blog-header">
                    <img src="/assets/imgs/profile.jpeg" alt="User avatar" class="avatar">
                    <div class="blog-info">
                        <h3>Building Responsive Layouts in 2025</h3>
                        <p class="author">By Mahesh • 5 days ago • Design</p>
                    </div>
                </div>
                <div class="blog-content">
                    <p>Mobile-first design is no longer optional. Here's my approach to creating truly responsive layouts that work flawlessly across all devices...</p>
                </div>
            </div>
        </div>
    </main>

    <footer>
        <p>&copy; 2025 BlogSpot. All rights reserved.</p>
    </footer>
</body>
</html>
