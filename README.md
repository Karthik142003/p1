System.setProperty("webdriver.chrome.driver", "C:\\Users\\User\\Downloads\\chromedriver-win64\\chromedriver-win64\\chromedriver.exe");
		ChromeDriver d=new ChromeDriver();
		d.manage().window().maximize();
		d.get("https://vvce.ac.in/");
		d.manage().timeouts().implicitlyWait(10,TimeUnit.SECONDS);
		d.findElement(By.xpath("//*[@id=\"page\"]/div[2]/div/div/section[1]/div[1]"));
