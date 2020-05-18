@istest
private class AnimalLocatorTest {
    @istest static void AnimalLocatorMock1() {
Test.SetMock(HttpCalloutMock.class, new AnimallocatorMock());
string result = AnimalLocator.getAnimalNameById(3);
string expectedResult = 'cow';
System.assertEquals(result, expectedResult);
    }
}
