Submission of Project 1


Assignment
----------
Show the following codes and results:
* Loading the data and preprocessing.  
  1. Loading data using read.csv().    
  2. Processing the data into a format fit for analysis.  
* What is the mean total number of steps taken per day?  
  1. (Ignoring NA values) calculate the total number of steps taken per day.  
  2. Make a histogram of the total number of steps taken per day.  
  3. Compute the mean and median of the total steps per day.  
* What is the average daily activity pattern?
  1. Make a time series plot (i.e. type = "l") of the 5-minute interval (x-axis) and the average number of steps taken, average across all days (y-axis).  
  2. Which 5-minute interval, on average across all the days in the dataset, contains the maximum number of steps?  
* Imputing missing values. Presence of NA days may introduce bias into some calculations or summaries of the data.  
  1. Calculate and report the total number of mising values in the data set (total number of rows in NA).  
  2. Devise a strategy for filling in all of the missing values in the data set. Example, the mean or median for the day could be used or the mean for the five minute interval.  
  3. Create a new dataset that is equal to the original dataset with the missing NA values filled in.  
  4. Make a histogram of the total number of steps taken each day, Calculate and report the median and mean total number of steps per day. How do these values compare to the cases where NA values were simply ignored? What is the impact of imputing missing data on the estimates of the total daily number of steps taken?  
* Are there differences in activity patterns between weekdays and weekends? weekdays() function might be useful for this part. Use the data set with the filled in missing values.  
  1. Create a new factor variable in the dataset with the two levels - "weekdays" and "weekend".  
  2. Make a panel plot containing the time series plot (i.e. type = "l") of the five-minute interval and the average number of steps taken averaged across all weeday days and weekend days (y-axis).  