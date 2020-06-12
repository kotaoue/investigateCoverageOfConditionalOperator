# investigateCoverageOfConditionalOperator
Investigate coverage of conditional operator.

## Result
*
  ```
  ./vendor/bin/phpunit --bootstrap src/Target.php tests/TargetTest.php --coverage-text > ./build/coverage-report.txt
  ```  
  -> [result](build/coverage-report.txt)
* 
  ```
  phpdbg -qrr ./vendor/bin/phpunit --bootstrap src/Target.php tests/TargetTest.php --coverage-text > ./build/coverage-report-phpdbg.txt
  ```  
  -> [result](build/coverage-report-phpdbg.txt)