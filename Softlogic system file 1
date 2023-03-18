package SLA_Project;
import org.openqa.selenium.By; 
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.WebElement;
import org.openqa.selenium.chrome.ChromeDriver;
import org.openqa.selenium.firefox.FirefoxDriver;
import org.openqa.selenium.interactions.Actions;
import org.openqa.selenium.support.PageFactory;
import org.testng.annotations.Test;
import SLA_Project.findsla;
public class sla_access {
		@Test
		public void sla() throws InterruptedException {
			
			System.setProperty("webdriver.chrome.driver", "E:\\Programing\\Drivers 2\\chromedriver.exe");
	    WebDriver d=new ChromeDriver();
			d.get("https://www.softlogicsys.in/");
			Thread.sleep(30000);
			d.manage().window().maximize();
			
			PageFactory.initElements(d, findsla.class);
			
			// Training Courses
			
			Actions build = new Actions(d);
			WebElement pyth=d.findElement(By.xpath("//*[@id=\"menu-item-1718\"]/a/span"));
			build.moveToElement(pyth).perform();
			findsla.pyth.click();
			
			WebElement mler =d.findElement(By.xpath("//*[@id=\"menu-item-1718\"]/a/span"));
			build.moveToElement(mler).perform();
			findsla.mler.click();
			
			WebElement rpro =d.findElement(By.xpath("//*[@id=\"menu-item-1718\"]/a/span"));
			build.moveToElement(rpro).perform();
			findsla.rpro.click();
			
			// placement
				WebElement psl =d.findElement(By.xpath("//*[@id=\"menu-item-1926\"]/a/span"));
				build.moveToElement(psl).perform();
				findsla.psl.click();
				
				WebElement interview=d.findElement(By.xpath("//*[@id=\"menu-item-1926\"]/a/span"));
				build.moveToElement(interview).perform();
				findsla.interview.click();
				Thread.sleep(1000);
				
				WebElement internship=d.findElement(By.xpath("//*[@id=\"menu-item-1926\"]/a/span"));
				build.moveToElement(internship).perform();
				findsla.internship.click();
				
				//company
				WebElement whysof=d.findElement(By.xpath("//*[@id=\"menu-item-1956\"]/a/span"));
				build.moveToElement(whysof).perform();
				findsla.whysof.click();
				
				WebElement eigh=d.findElement(By.xpath("//*[@id=\"menu-item-1956\"]/a/span"));
				build.moveToElement(eigh).perform();
				findsla.eigh.click();
				
				WebElement gallery=d.findElement(By.xpath("//*[@id=\"menu-item-1956\"]/a/span"));
				build.moveToElement(gallery).perform();
				findsla.gallery.click();
				
				//Masters Program
				WebElement dsp=d.findElement(By.xpath("//*[@id=\"menu-item-1921\"]/a/span"));
				build.moveToElement(dsp).perform();
				findsla.dsp.click();
			
				//More Coruses 

				WebElement ps=d.findElement(By.xpath("//*[@id=\"menu-item-3262\"]/a/span"));
				build.moveToElement(ps).perform();
				WebElement pupet=d.findElement(By.xpath("//*[@id=\"menu-item-1777\"]/a/span"));
				build.moveToElement(pupet).perform();
				findsla.p.click();
				
				WebElement pt=d.findElement(By.xpath("//*[@id=\"menu-item-3262\"]/a/span"));
				build.moveToElement(pt).perform();
				WebElement p3=d.findElement(By.xpath("//*[@id=\"menu-item-3441\"]/a/span"));
				build.moveToElement(p3).perform();
				findsla.thirt.click();
				
				WebElement p=d.findElement(By.xpath("//*[@id=\"menu-item-3262\"]/a/span"));
				build.moveToElement(p).perform();
				WebElement automation=d.findElement(By.xpath("//*[@id=\"menu-item-1754\"]/a/span"));
				build.moveToElement(automation).perform();
				findsla.automation.click();
				
				d.quit();
		}
	}
